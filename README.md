# BabyStepper
DIY Equatorial Camera Mount

Sorry if anything is incorrect, i'm no professional, but the result did work for me.

I wanted to start Astrophotography but i do not have the Money for those 300-600€ mounts which dont event fit my needs perfectly so i started desiging my own one. I spent roughtly 70€ for my Setup. This is what i came up with. 

A single Axis, wich is driven by a high precision planetary geared Nema 17, compensates the Rotation of the Earth, when correct aligned.
The Brain of the Mount is a ESP32, operating an A4988 driver. This is set to 1/16 Stepping
The gearratio is 1/30/30 with 1/16 Stepping, this equals to 2.880.000 Steps/Revolution or 8.000 Steps/°Deg.

3D-printed Parts                                            
1: Casing                           
2: Axis with integrated wormwheel                                       
3: Wormgear                                           
4: Mountadapter                                 
5: (optional) Controllertray                                          


Purchased Parts:
Those links are only suggestions, which i have used to order parts

1: 2x Ballbearing 45x58x7mm  dxDxb                                        
https://www.kugellager-express.de/rillenkugellager-6809-2rs-61809-2rs-45x58x7-mm

2: 1x Ballbearing 12x28x8mm  dxDxb                                                
https://www.kugellager-express.de/rillenkugellager-6001-2rs-12x28x8-mm

3: 1x ESP32                                 
https://www.banggood.com/ESP32-Development-Board-WiFi+bluetooth-Ultra-Low-Power-Consumption-Dual-Cores-ESP-32-ESP-32S-Board-p-1109512.html?rmmds=myorder&cur_warehouse=CZ

4: 1x A4988 Stepper Driver                          
https://www.banggood.com/Geekcreit-3D-Printer-A4988-Reprap-Stepping-Stepper-Motor-Driver-Module-p-88765.html?rmmds=myorder&cur_warehouse=CN

5: 1x Nema 17 geared Stepper Motor                                            
https://www.omc-stepperonline.com/de/prazisions-planetengetriebe/ausverkauf-nema-17-schrittmotore-l-39mm-getriebeubersetzung-30-1-hohe-prazision-planetengetriebe.html
Note: The Stepper motor is with 50€ by far the priciest Part, but every so often this motor is on sale at OMC Stepperonline (I got 28.09% discount)

6: 1/4 to 3/8 Screws                              
https://www.amazon.de/MENGS%C2%AE-M%C3%A4nnlich-Schraube-Edelstahl-Material-Wei%C3%9F/dp/B00IUCL46E/ref=sr_1_6?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=3%2F8+schraube&qid=1606388895&sr=8-6

7: M10x120mm Screw and nut for connecting the Adapter to the Casing.      
bought from the local Hardwarestore


The Esp32 is set up to listen on the Serialbluetooth port, wich means Babystepper is controlled via Bluetooth. To sent those commands to the Esp32 the easiest Way is to download/use the APP "Serial Bluetooth Monitor", another way to operate the mount would be to write an App for the Serial communtication, which i did.

Sice it is "done" i was able to try it only once. The result was quite pleasing.It works but my major problem is still aligning with Polaris, because i dont have any scope, i put my smartphone next to the Mount an open up Stellarium with wich i Align with Polaris. this Method is quite inaccurate, but can work after some finetuning.
The Picture i uploaded was 306seconds exposed with an Aperture of F1.6 at 50mm, with a Nikon D800 DSRL. Small Trailings are still visible.

Please leave any Suggestions for Improvement!
