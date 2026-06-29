<picture> <source media="(prefers-color-scheme: dark)" srcset="Images/logo-white.png" width="800"> <img src="Images/logo-dark.png" width="800"> </picture> 

<img src="Images/img1.JPG" width="400" />  <img src="Images/img2.JPG" width="335" /> 
<img src="Images/render-front.png" width="380" />  <img src="Images/render-back.png" width="355" /> 

# Introduction 
The N64-PSU is a simple, compact, cheap and open-source Nintendo 64 Power Supply Unit. 
It can be used to power trimmed Nintendo 64 motherboard, or builds like the [Matterhorn 64 Core](https://github.com/Xenii1642/Matterhorn-64-CORE/)
This board is based on the [CrazyGadget's PSU-PLUS](https://github.com/CrazyGadgetMods/PSU-Plus). 
Further information can be found on this [BitBuilt Post] SOON

# Caracteristics 
- Input voltage from 6V to 18V
- 3.3V Regulator
- 5V Regulator
- Up to 3A per rail
- 16x25mm form factor
- Price under $5 per unit 

# Ordering
The PCB Gerbers files are available in the [Gerbers folder](https://github.com/Xenii1642/N64-PSU/tree/main/Gerbers) of this repository. 
They can be ordered through either [PCBway](https://www.pcbway.com/), [JLCPCB](https://www.jlcpcb.com/) or the manufacturer you want. 

Components are listed in the [BOM.pdf](https://github.com/Xenii1642/N64-PSU/blob/main/BOM.pdf) file, and can be ordered through [Digikey](https://www.digikey.com/)

# Connection Diagram
The N64-PSU can be connected to a Nintendo 64 motherboard as shown:
<img src="Images/diagram.png" width="800" />

⚠️ It is highly recommended to remove the original 12 to 5V LDO (U13) ⚠️

⚠️ Never power the console by both the original power supply and the N64-PSU as the same time.
This will damage and destroy the voltage regulators of the N64-PSU. ⚠️

For further information, please take a look at the [N64 Trimming Guide](https://bitbuilt.net/forums/threads/the-advanced-n64-trimming-guide.3992/) on [Bitbuilt.net](https://bitbuilt.net/forums/)

Any modified versions of derivatives must also remain open-source under the same, unmodified license.
You must also properly credit the original creators when reusing or redistributing these files.

# Support
If you notice anything wrong with this design, please let me know! 
You can also reach to me for questions or general help, I'm always happy to help 👍

Thank you for your support and see you next time!
