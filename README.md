<!--- 
Open Source Assistive Technology: GitHub Readme Template
 --->

<!---
INSTRUCTIONS
This is a markdown template for creating the README.md file in a GitHub repository. This file is rendered and displayed automatically when someone visits the repository.

This document includes helper text that will not be displayed when rendered. Any text between the less-than sign + exclamation mark + three hyphen-minus (<!---) and matching three hyphen-minus + greater-than sign will not be displayed. This helper text can be deleted once the corresponding section is completed.

 --->
 
 <!--- 
TITLE
Should match the name of the GitHub repository. Choose something descriptive rather than whimsical. 
 --->
 # Oak Compact Joystick

<!--- 
SUMMARY
A brief summary of the project. What it does, who it is for, how much it costs.
 --->
The Oak Compact Joysticks are medium sized analog gaming joysticks that have 4 interchangeable toppers and are compatible with PC (USB Version) and the XAC (Both USB and non-USB versions). They have an approximately ±25° range of motion and moderate force to operate. The non-USB version (A) has a 3.5 mm TRRS plug (the size of a headphone jack) and can be used to play games with the Xbox Adaptive Controller (XAC). It may be compatible with other interfaces that use joysticks with 3.5 mm TRRS cables, such as the [Enabled Controller](https://makersmakingchange.com/project/enabled-controller/).

These current devices exist as prototypes with some of the following updates on the way:
- Switch itegration
- Updated code for improved user response profiles
- Increase in mounting options
- Increase in topper options

<!--- 
PHOTO

 --->
![Image Description](Photos/USB_Joystick_2.jpg)

<!--- 
## More info at
 - [Makers Making Change Forum Thread](TBD) 
 - [Makers Making Change Project Page](TBD)
 --->


## Getting Started
<!--- 
Include an overall idea of what major steps are required to build the device.
 --->
### 1. Verify Which Design the User Wants
The Oak Compact Joystick comes in both USB (U) and Non-USB (A) format. The non-USB version uses a [TRRS](https://www.sparkfun.com/products/11580) lead to conncet to an existing gamepad such as the XAC or [Enabled Controller](https://makersmakingchange.com/project/enabled-controller/). The USB version has its own microcontroller and allows for direct PC use as well as some customisation of the joystick responce profile. Ask the user which one they would like. There are separate set of documentation for each joystick version.

Other available joysticks can be found through the [Joystick Selection Guide](https://makersmakingchange.com/resource/analog-joystick-selection-guide/)

### 2. Order the Off-The-Shelf Components
The Bill of Materials lists all of the parts and components required to build the Oak Compact Joystick. The mechanical components may be available locally, but will probably need to be ordered online. 

### 3. Print the 3D Printable components
Print the components for the Oak Compact Joystick enclosure.

All of the files and individual print files can be in the [/Build_Files/3D_Print_Files](/Build_Files/3D_Print_Files/) folder.

### 4. Assemble the Oak Compact Joystick
Reference the Assembly Guide for the tools and steps required to build each portion. 

## Files
<!---
FILES
This section includes all the information and files required to build and modify the device, including documentation, design files, and build files. 
--->

### Documentation
<!---
DOCUMENTATION

--->
| Document             | Version | Oak Compact Joystick - U 														| Oak Compact Joystick - A |
|----------------------|---------|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| Design Rationale     | 0.2     | [Oak_Compact_Joystick_Design_Rationale](/Documentation/Oak_Compact_Joystick_Design_Rationale.pdf)       	| [Oak_Compact_Joystick_Design_Rationale](/Documentation/Oak_Compact_Joystick_Design_Rationale.pdf)      |
| Maker Checklist      | 0.2     | [Oak_Compact_Joystick-U_Maker_Checklist](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick-U_Maker_Checklist_v0.2.pdf)     	| [Oak_Compact_Joystick-A_Maker_Checklist](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick-A_Maker_Checklist_v0.2.pdf)     |
| Bill of Materials    | 0.2     | [Oak_Compact_Joystick-U_Bill_of_Materials](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick-U_BOM_v0.2.csv)     		| [Oak_Compact_Joystick-A_Bill_of_Materials](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick-A_BOM_v0.2.csv)     |
| 3D Printing Guide    | 0.2     | [Oak_Compact_Joystick-U_3D_Printing_Guide](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick-U_3D_Printing_Guide_v0.2.pdf)     | [Oak_Compact_Joystick-A_3D_Printing_Guide](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick-A_3D_Printing_Guide_v0.2.pdf)     |
| Assembly Guide       | 0.2     | [Oak_Compact_Joystick-U_Assembly_Guide](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick-U_Assembly_Guide_v0.2.pdf)     	| [Oak_Compact_Joystick-A_Assembly_Guide](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick-A_Assembly_Guide_v0.2.pdf)     | 
| User Guide           | 0.2     | [Oak_Compact_Joystick-U_User_Guide](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick-U_User_Guide_v0.2.pdf)    		| [Oak_Compact_Joystick-A_User_Guide](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick-A_User_Guide_v0.2.pdf)    |
| Changelog            | 0.2     | [Oak_Compact_Joystick-U_Changelog](/Documentation/Oak_Compact_Joystick-U/Oak_Compact_Joystick_Changelog_v0.2.pdf)     			| [Oak_Compact_Joystick-A_Changelog](/Documentation/Oak_Compact_Joystick-A/Oak_Compact_Joystick_Changelog_v0.2.pdf)     |

### Design Files
<!---
DESIGN FILES
If possible, include a copy of original design files to facilitate easy editing and customization.
--->
 - [CAD Files](/Design_Files)

### Build Files
<!---
BUILD FILES
This section i
--->
 - [3D Printing Files](/Build_Files/3D_Print_files)
 - [Firmware](/Build_Files/OpenAT_Joystick_Software_Oak)

## License
<!---
LICENSE
Choose an appropriate license. We recommend an open-source hardware compatible license.
--->
Everything needed or used to design, make, test, or prepare the Oak Compact Joystick is licensed under the CERN 2.0 Weakly Reciprocal license <https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2> (CERN-OHL-W).

Accompanying material such as instruction manuals, videos, and other copyrightable works that are useful but not necessary to design, make, test, or prepare the Oak Compact Joystick are published under a Creative Commons Attribution-ShareAlike 4.0 license <https://creativecommons.org/licenses/by-sa/4.0/> (CC BY-SA 4.0).

## Attribution
<!---
ATTRIBUTION
Include any information related to the development of the design. This may include who identified the initial challenge, who contributed to the design
--->
Designer: Stephen Moyer, MMC

The documentation template was created by Makers Making Change and is used under a CC BY-SA 4.0 license. It is available at the following link: https://github.com/makersmakingchange/OpenAT-Template




## About Makers Making Change
<img src="https://www.makersmakingchange.com/wp-content/uploads/logo/mmc_logo.svg" width="500" alt="Makers Making Change Logo">

Makers Making Change is an initiative of [Neil Squire](https://www.neilsquire.ca/), a Canadian non-profit that uses technology, knowledge, and passion to empower people with disabilities.

We are committed to cultivating a network of volunteer makers who support people with disabilities in their communities through cost effective assistive technology. Check out our library of free, open-source assistive technologies.

 - Website: [www.MakersMakingChange.com](https://www.makersmakingchange.com/)
 - [GitHub](https://github.com/makersmakingchange)
 - [Thingiverse](https://www.thingiverse.com/makersmakingchange/about)
 - Twitter: [@makermakechange](https://twitter.com/makermakechange)
 - Instagram: [@makersmakingchange](https://www.instagram.com/makersmakingchange)

### Contact Us
For technical questions, to get involved, or to share your experience we encourage you to visit [MMC Forum](https://forum.makersmakingchange.com) or contact info@makersmakingchange.com
