# Acheron 60-SM-S-ATM32U4-MX-TH-WI (Codename "ArcticPCB")

Table of Contents
=================

  * [Project overview](#project-overview)
  * [Frequently Asked Questions (FAQ)](#faq)
  * [Board preview](#board-preview-version-31)
  * [Changelog](#changelog-and-version-control)
  * [Bill of Materials](#bill-of-Materials)
  * [Acknowledgements](#Acknowledgements)
  * [License](#license)

## Project overview

The ArcticPCB is a freely available, open-source 60% staggered keyboard Printed Circuit Board (PCB), designed to support most 60% layouts like ANSI, HHKB, Tsangan bottom row. As in all the boards in the Acheron Project, the resources and software used to design this board are open-source and/or freely available.

Here's a list of the board's features:

- ARM Cortex M4-based STM32F303 processor;

- QMK firmware compatible;

- USBC type connector;

- RGB underglow through intelligent integrated controller WS2812B LEDs;

- Multi-layout support;

- Hardware reset through a push button and reset network;

- Overcurrent and overvoltage input protection through a fuse and schottky diode;

- Electrical Static Discharge (ESD) protection through a discharge net.

Additionally, plate gerber files are also available so that the user can order them made from the same manufacturer as the PCBs and out of the same material (FR4, a fiberglass enhanced resin laminate). This makes production cheaper and faster.

There are four plate designs available: one for each supported layout and a universal one that supports all three of them.

## FAQ 

<!-------------------------------------------------------------------->

<details><summary> Is this design functional and tested? </summary>

> Yes. As of the first version, this board was prototyped and works.

</details>

<!-------------------------------------------------------------------->

<details><summary> How can I obtain this PCB? Is there an IC or a GB thread? </summary>

> As it is right now (version 1.0), there are no plans to make any IC or GB threads. There are two reasons for this. The first one is that this was the first hobbyist brazilian mechanical keyboard project, and the intent was to test how the brazilian community would receive such an edeavour. Second, this board has certain outadted features --- like using an ATMEGA32U4 processor and a USB mini connector. The next version will feature an STM32 processor and a USBC connector.

</details>

<!-------------------------------------------------------------------->

<details><summary> Where are you planning to distribute this board? </summary>

> Since this project is still in the development stage, no plans to distribute the board are available.

</details>

<!-------------------------------------------------------------------->

<details><summary> How much will this board cost? </summary>

> We are aiming at a US$30,00 mark.

</details>

<!-------------------------------------------------------------------->

<details><summary> Will you (or anyone in the Acheron Project) profit from this project? </summary>

> I won't profit from it myself, although I retain a little portion of the gains to fund further projects, that is, to maintain prototyping, components and overall design costs. A famous brazilian writer, Millôr Fernandes, once said: "never trust an idealist that profits from his ideals".

> If I find commercial partners in other continents than they'll probably have my express permission to use the deisgns commercially, so I won't be able to tell them if they can profit or how much they will. It's, of course, in the best interest of everyone that the boards are as cheap as possible.

</details>

<!-------------------------------------------------------------------->

<details><summary> Who is funding this project? </summary>

> I and MrKeebs are, although mostly on his part since I'm a broke university student.

</details>

<!-------------------------------------------------------------------->

<details><summary> Can anyone contribute to this project? </summary>

> Anyone is welcome to contribute, be it through feature requests, opinions or criticisms. This can be done through the GeekHack posts, issues and questions on GitHub or even through my Discord (#Gondolindrim#9738). If you want to actively contribute to the design, feel free to contact me and we'd be glad to have you. 

</details>

<!-------------------------------------------------------------------->

<details><summary> Why open-source? </summary>

> As I don't intend to profit from this, there is no reason to keep the design closed. I also have the opportunity to contribute to the open-source way of thinking: many heads are better than one. Following these steps I use only open-source stuff to design the keyboards: the ECAD design is made with KiCad, the renders and animations in Blender, the logo design in Inkscape. All these software are run on Arch Linux, which is a Linux distro heavily based on the OSS and KISS principles.

> By adopting free OSS tools any newbie makers can take a look and learn from these designs, that is, I also have an educational reason in mind. In this regard, I also have a transparency principle, that is, anyone in the community can contact me and ask questions about the project and the design decisions or the design process. Any maker can also check my designs and points its flaws.

> Second, there is also the KISS (Keep It Simple, Stupid!) principle in mind. Since this project is completely un-ambicious, I try to keep it as simple as possible, so that the design and community processes are fluid.

</details>

<!-------------------------------------------------------------------->

<details><summary> And why publish the design under a share-alike non-commercial license? </summary>

> The reason for the license is twofold: first, while I want the design to be open-source, that is, educational and freely available, I think it's not just that someone could just take it, make little adaptations (like changing the logos) and profitting from it when the idea of the project is to have the open-source ideas in mind. It's not about myself -- although of course I have some pride in my designs and like to have credit for them -- but about the project ideals.

> Second, I don't condemn the idea of commercializing my designs, I'd just like to know who is selling it so that I can have a good quality control.

</details>

<!-------------------------------------------------------------------->

<details><summary> What resources and software do you use? </summary>

> All the footprints and symbols are available wither on the KiCad libraries or my MX library, which contains footprints and symbols for some components not available on KiCad.

> The design, footprints and symbols are made through KiCad. The 3D models are obtained in sites where the content is free and widely available like 3D Content Central and GrabCad Community, and to edit them I use FreeCAD.

> The logos were designed in Inkscape. The base image was taken from [this page](https://www.vectorportal.com/StockVectors/Animals/SHARK-ILLUSTRATION/15844.aspx) (last access: 26 feb, 2019). Although stated in the Vector Portal site that the designs are freely available to be used in commercially, I tried to contact the uploader, who goes by the name of "Yohan Plantec" with no success.

> The renders and animations are made in Blender.

</details>

<!-------------------------------------------------------------------->

<details><summary> How can I follow your design process and learn from this project? </summary>

> I try to stream my design processes when I can. I generally do it at tuesdays and thursdays at 3PM PST (8PM BRT). In the streams I answer general electronics questions, and show how the board is designed. I stream at my [Twitch channel](http://twitch.tv/gondolindrim_). The past streams can be seen in my Youtube channel.

</details>

## Board preview

To be disclosed.

<!-- ![Alt text](./renders/frontRender.png)

![Alt text](./renders/backRender.png) -->

## Changelog and version control

<details>
 <summary> <font size="+2"><b> 2019/01/12 (V1.0) </b></font></summary>
 <p>

 <h6> Initial version commited. </h6>

</p></details>


## Bill of Materials

To be disclosed.

<!--- In the ./bom/ folder there is an .xlsx file that can be uploaded directly into the LCSC site. The file contains all LCSC part numbers, quantities and descriptions. 

If you don't want to order them from LCSC, the table below can be used.

| Description  | Value | Package | Quantity |
| ------------- | :-------------: | :-------------: | :-------------: |
| USB Connector | - | TYPE-C-31-M-12  | 1 |
| C1 and C2 | 22pF | 0805  | 2 |
| C7, C9, CRST1, CRST2 | 4.7nF | 0805| 4 | 
| (Poly)Fuse | 1.5A trip | 0805 | 1 | 
| R5 and R6 | 1MOhm | 1206 | 2 | 
| Q1 | AO4406AL | SOIC8 | 1 | 
| CSin1, CSout1, CVBus1-3, CA1, CB1 | 100nF | 0805 | 7 | 
| CVBus4 | 1uF | 0805 | 1 | 
| CVBus5 | 4.7uF | 0805 | 1 | 
| DF1 | RB060M-60TR Schottky Diode | SOD-123 | 1 | 
| QRST | BC846 NPN BJT | SOT-23 | 1 | 
| RCC | 5.1kOhm | 1206 | 1 | 
| RD+ and RD- | 22ROhm | 1206 | 2 | 
| RD+Up | 1.5kOhm | 1206 |  1 | 
| RPGate, RB1/2, RA1/2 | 10kOhm | 1206 | 5 | 
| RRST | 100kOhm|  1206	| 1 | 
| RSGate1 | 1kOhm | 1206 | 1 | 
| SWRST1 |SMD Push Button | - | 1 | 
| U1 | STM32F303CCT6 | LQFP48 | 1 | 
| U2 | MCP1700-330 LDO | SOT23 | 1 | 
| Y1 | 8MHz 4 pin SMD Crystal | 5032 | 1 | 
| RGB | WS2812B | - | 8 | 
| RL1-RL | 360 Ohm | 1206 | 50 | 
| D1-48, DS1 and DRST | 1N4148W | SOD123 | 52 |
| ROT1 | ALPS EC11Ex (see note 1) | - | 1 |

(1) Any EC11Ex rotary encoder should be fine, as the models differ only on shaft shape and size but their footprints are the same. In the render I used the ALPS EC11E 15244G1. -->

## To-do list

### Design 
- [ ] Port the design to the STM32F303CCT6 processor.
- [ ] Change the connector to the USBC version.
- [ ] Add per-switch LEDs.
- [ ] Add underglow LEDs.

### Prototypes
- [ ] Prototype the board
- [ ] Build the board
- [ ] Test the prototypes
- [ ] (Eventually) Correct bugs

### Distribution
- [ ] Made IC thread
- [ ] Made GB thread
- [ ] Started GB

## Acknowledgements

Although there is only me actively working on the project design, some acknowledgements are due:
  * Felipe "MrKeebs" Gonçalves and Raphael "ArcticFox" Hochheim. Dear friends and always up to help with my questions; Arctic was an inspiration for this board with his MK knowledge.

## License

This project is licensed under the Creative Commons Non-Commercial Share-Alike 4.0 license, available in (https://creativecommons.org/licenses/by-nc-sa/4.0/).

To know more about why I published the project under this license, please look at the [FAQ section](#faq).
