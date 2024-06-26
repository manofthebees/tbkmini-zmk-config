# a ZMK [TBKmini](https://github.com/bastardkb/tbk-mini)
The designer of the keyboard is Quentin Lebastard of [bastardkb](https://bastardkb.com)

I really liked the design but I'm not a big fan of cables 😅
so i decided to build a wireless version using ZMK & handwiring

Unlike other wireless handwire builds I did not use the nice!nano. I used the [Seeed Studio XIAO nRF52840](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html).

# pictures!
<p align=left>
<img src="images/1.JPEG" >
<img src="images/2.JPEG" >
<img src="images/3.JPEG" >
<img src="images/with-unit01.JPEG" >
</p>

# keymap
<p align=left>
<img src="images/kmA.png" width="5500" >
<img src="images/kmB.png" width="5500" >
<img src="images/kmG.png" width="5500" >
</p>

# build process

BOM is the same as the regular tbkmini sans the PCBs with the addition of 2 XIAO BLEs & 2 batteries. I just used ones I pulled from old wireless travel keyboards (ship of theseus much lol). Just make sure the dimensions are less than 35mmx20mm

After printing the two halfs & their respective bottom plates, I noticed that the XIAO BLE was small enough where the USB-C port fit perfectly into the port that was modelled in. 

## I designed a mount for XIAO BLE that also has space for a [pushbutton switch](https://www.amazon.ca/Tact-Tactile-Push-Button-Switch/dp/B0087ZF3J8?th=1), that used the existing mounting holes 

<div class"img1-wit-txt" align=center>
<img src="images/xiao-holder.png" alt="xiao TBKholder">
<p><em>xiao TBKholder</em></p>
</div> 

## my battery mounting solution is rather jank 😅 

<div class"img2-wit-txt" align=left>
<img src="images/back.JPEG" alt="battery mounting">
<p align= center><em>it's just glued to the plate lol</em></p>
</div> 

I plan to improve the mounting solution when I get time & get access to the plate source file, maybe even get something milled 😲

# matrix wiring
this was also uber jank, the orders for the column pins are inverted between the left & the right because I decided to "fix it in post" rather than changing the wiring :P
<div class"img34-wit-txt" align=center>
<img src ="images/leftpins.png" alt="left col pins">
<p><em>left col pins</em></p>
<img src ="images/rightpins.png" alt="right col pins">
<p><em>right col pins</em></p>
</div>

# special thanks <3
- ### Quentin Lebastard - [bastardkb](https://bastardkb.com)
- ### Peter Johanson - for making [ZMK](https://zmk.dev/)!
- ### Nick Coutsos - for making the excellent ZMK [keymap editor](https://nickcoutsos.github.io/keymap-editor/) webapp!

