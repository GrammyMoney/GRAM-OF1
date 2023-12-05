# Open GRAMv2

# Introduction 
**Open GRAMv2** was borne from a desire to create a premium digital controller chassis that allowed for maximum flexibility in design, while also optimizing for cost. The main component is an SLA-printed resin frame that allows for customized top and bottom panels. This enables a variety of customizations all based on the same initial framework. The v2.0 model supports soldered MX switches (hotswaps are technically possible, but have not been tested and may reduce stability).

**If you would like to support the developer of this project, consider purchasing parts like buttons, USB-C to GCC cables, and official GRAM builds at [grammy.money](https://www.grammy.money) rather than a fab house.**

![DSC00547](https://github.com/GrammyMoney/Open-GRAMv2/assets/126632196/f23fd78b-600b-430f-9778-1781b8d7736d)


Included Files
-
Included in this repo is all the files needed to get started with a simple GRAMv2 build:
- **GRAMv2 Frame .stl files** (with and without logo)
- **Fab files for GRAMv2 top and bottom panel** (blank with GRAM logo in bottom corner)
- **Template DXF** for customizing top and bottom panels
- **Fab Files for Switchplate**
- **Inner standoff .stl files**
- **GRAM-profile MX button .stl files** (for more info, check out the GRAM-MX repo here: [coming soon!])

Additional Information
-
If you want more info around GRAM builds, both open source and official builds, please join the [GRAM Digital Controllers Discord](https://discord.gg/6TuHw2r2X4) to ask questions and work with the community! I would love to see people creating new interesting designs, and building upon the initial framework. This build is far from perfect, but it is an incremental update in what I hope will be a long development history.

Thanks & Acknowledgements
-
There are several people who made this project possible, either directly or indirectly.
- Obviously [Greg](https://twitter.com/Greg_Turbo) at Frame1 for developing the original OF1 board.
- [Bjart](https://twitter.com/bjartskular2), who developed the OFOF1 chassis, which was the initial development for a lot of the ideas explored in this build, including using PCB fabs for the panels, and the general idea of stacking two panels on a frame for the enclosure.
- [TheSaltiestSea](https://www.thingiverse.com/thing:4921072), for developing amazing button .stl's that served as inspiration for my custom MX button profile.
- Finally, my partner Nik for putting up with long nights of me ranting about digital controllers and a 22-year-old children's video game.

# Ordering & Customization Guide
While most of these files are universal and can be used at any fab house, **JLCPCB** has become the de-facto standard for DIY box manufacturing. This is due to their hyper-affordable pricing and low minimum order quantity.

The PCB
-
The PCB Fabrication files and ordering guide can be found on the [Open-Frame1 Repo](https://github.com/GregTurbo/Open-Frame1) and in the Frame1 discord.

The Panels
-
The panel Fab Files are located in *Panels>Fab-Files*. If ordering from JLCPCB, load the ZIP files into their automated quoting tool. For a more premium build, I recommend aluminum panels.

**IMPORTANT NOTE: You may need to manually input the dimensions of the panels. These are _368.3mm_ and _177.8mm_.**

![image](https://user-images.githubusercontent.com/126632196/223051246-1ae2c207-90c1-4d03-98f3-579bc118795f.png)

To customize panels in KiCAD, import the template DXF into KiCAD on the **edge-cuts** layer. All customized designs should be made to fit 14.5" x 7" and imported through the image conversion tool onto the silkscreen layer (less complex designs can be put on the solder mask layer if you're doing black aluminum).

The Frame
-
When printing the frame with JLC, The recommended materials are:
- **LEDO 6060** (natural white, goes well with matching buttons and black panels)
- **Black Resin** (matte grayish-black, goes well with both black and white panels)
- **PA12-HP Nylon** (Much more expensive given the print volume, but gives an amazing textured finish)

![image](https://user-images.githubusercontent.com/126632196/223052352-a4c2d55a-cfc7-4572-8304-fdd36269bb7d.png)

The Buttons
-
The buttons included in this repo are a completely custom profile with rounded edges and a slight concave. I have dubbed these GRAM profile MX buttons. While any F1 style button (20-21mm, MX-style stem) will work, these are my personal preference after 4+ iterations.

The buttons have been tested in the same three materials:
- **LEDO 6060** (natural white, most cost-effective option, goes well with matching frame and black aluminum panels)
- **Black Resin** (matte grayish-black, goes well with both black and white panels)
- **PA12-HP Nylon** (Only slightly more expensive for buttons, but gives an amazing textured finish, very premium feel)

Included in the "Buttons" folder is 3 .stl files:
- **Solo** is a single button. The GRAM Profile MX Buttons are designed to be universal in terms of manufacturing, and they have all the draft angles necessary to create silicone molds for resin casting. This enables you to create custom buttons in a similar way to custom GCC modders, with all the creativity and expression that comes with it.
- **10pc** is the multi-part print I recommend for cost effectiveness at JLC. Due to JLCPCB rules, you cannot create a multipart print that has more than 10 identical small parts within it, so this is the best bang for your buck. As of March 2023, Running 2 prints of this for 20 buttons in LEDO 6060 costs only $3.14.
- **20pc** is the largest multipart print I prepared for this release. If you are printing on your own printer, this .stl allows you to print a whole controller's worth of buttons in a single stroke. This print is untested, so attempt at your own risk.

The Standoffs
-
Similar to the buttons, these are printed in a multi-part .stl that allows for 10 pieces to be printed at once at JLCPCB. Each build needs 5, so each print will give you enough for two controllers. These can be printed in the cheapest resin you can find (since they will not be visible in the final build), which as of March 2023 is **9000R**.

# Build Guide

Building the GRAMv2 is relatively straightforward, but an updated in-depth build guide (including a video!) is currently in the works.







