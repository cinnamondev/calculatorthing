# calculatorthing
its a calculator thing? The coolest calculator to exist (real)

~~[Project Page](https://itscinnamon/projects/calculator/)~~
# Goals of this project

- Somewhere in between a graphing calculator and a programming calculator (or a combination?)
- Ease of input of hex and binary inputs (0-9 and A-F keys easily accessible)
    - it would be cool to make fast input of binary possible (ie actuators on the end for easy blind input)
- Easily storable variables and 'environment configuration'
- USB OTG? it would be nice to switch environments to 'configure' and import/export data easily
    - CSV / Data logger support (wonder if can get it to accept NI logger instrument?)
- Data storage -> SD CARD(s)
- Decent battery life and rechargeable -> swappable 18650's
- Expandable

# Ways of attempting the goals

- ESP32! beloved
    - can run a SMALL webserver on demand to allow upload/download of data and environment configuration (variables, etc) (with the use of a companion program it could be used to offload more difficult calculations, but we are probably getting ahead of ourselves)
        - use cases for data transfer: LaTeX conversion tool(?) seems annoying... can use calculator functions to create equations then "upload" to system as latex equations to be used in programs such as obsidian.
        -  Also data logger upload/download data (import csv, do statisticy stuff with it)
    - Easy to reconfigure, provide USB OTG that allows self firmware flashing if a setting in the calculator menu has been used OR if a jumper is shorted
    - Powerful enough to do most things easily, expansive enough for our needs (expandability) and has low idle usage (deep sleep)
- Way for modules/accessories to clip to casing (idc connector)
- idk
# Licensing

This project is licensed under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal.

[License notice](LICENSE.md)

[Copy of the license, for convenience](LICENSE-CERN.md)

EXTERNAL:

[License user guide](https://ohwr.org/project/cernohl/wikis/uploads/b88fd806c337866bff655f2506f23d37/cern_ohl_s_v2_user_guide.txt)

[The link that the license was obtained from](https://ohwr.org/cern_ohl_s_v2.txt)