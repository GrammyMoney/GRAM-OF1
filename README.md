# Open-GRAMv2
A premium chassis designed for the Open Frame1 platform.

# Introduction 
**Open GRAMv2** was borne from a desire to create a premium digital controller chassis that allowed for maximum flexibility in design, while also optimizing for cost. The main component is an SLA-printed resin frame that allows for customized top and bottom panels. This enables a variety of customizations all based on the same initial framework. The v2.0 model supports soldered MX switches (hotswaps are technically possible, but have not been tested and may reduce stability).

**If you would like to support the developer of this project, consider purchasing parts like buttons, USB-C to GCC cables, and official GRAM builds at [grammy.money](https://www.grammy.money) rather than a fab house.**

Included Files
-
Included in this repo is all the files needed to get started with a simple GRAMv2 build:
- **GRAMv2 Frame .stl files** (with and without logo)
- **Fab files for GRAMv2 top and bottom panel** (blank with GRAM logo in bottom corner)
- **Template DXF** for customizing top and bottom panels
- **Inner standoff .stl files**
- **GRAM-profile MX button .stl** (for more info, check out the GRAM-MX repo here: [coming soon!])

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

Panels
-
The panel Fab Files are located in *Panels>Fab-Files*. If ordering from JLCPCB, load the ZIP files into their automated quoting tool. For a more premium build, I recommend aluminum panels.

**IMPORTANT NOTE: You may need to manually input the dimensions of the panels. These are _368.3mm_ and _177.8mm_.**

![image](https://user-images.githubusercontent.com/126632196/223051246-1ae2c207-90c1-4d03-98f3-579bc118795f.png)

To customize panels in KiCAD, import the template DXF into KiCAD on the **edge-cuts** layer. All customized designs should be made in Illustrator or a similar vector art software on a 14.5" x 7" canvas, and imported to KiCAD as an SVG at 1.33333 scale on the **front-silkscreen** layer.

The Frame
-
When printing the frame with JLC, The recommended materials are:
- **LEDO 6060** (natural white, goes well with matching buttons and black panels)
- **Black Resin** (matte grayish-black, goes well with both black and white panels)
- **PA12-HP Nylon** (Much more expensive given the print volume, but gives an amazing textured finish)

![image](https://user-images.githubusercontent.com/126632196/223052352-a4c2d55a-cfc7-4572-8304-fdd36269bb7d.png)



