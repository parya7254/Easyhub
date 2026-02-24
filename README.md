# Easyhub
A USB 2.0 hub which converts 1 USB input to 10 USB outputs! Speeds might not be the fastest, but great for connecting lots of accessories to your computer!
The reason for making this project is to learn about making your own USB hubs and using the ICs needed to do this. I also want to make my own solution to a problem of not having enough USB ports on my conputer. While anyone could just buy a USB hub, I chose to make my own so that I can expand my knowledge about electronics. Hack Club's Blueprint Program has enabled me to do something ever since I became extremely intrersted in electronics since I was 10 years old, make my own PCB and get the nesessary funding to do it.

<img width="7022" height="4510" alt="image" src="https://github.com/user-attachments/assets/56b33783-fca5-4d7c-8963-9184a738991f" />

# How in the world did I make this?
I did a lot of reasearch on Google and learned about the basics of the SL2.1A chip and USB hubs. Then I created a new project in EasyEDA and designed the PCB and schematic while also learning some more from a Hack Club Jam found over here: https://jams.hackclub.com/batch/usb-hub I then decided later on that I want to daisy chain the USB hub ICs to bring the total USB ports to 10. Before doing that, I picked out my parts and decided that I will use stacked USB ports in the front and then single ports for the sides.

# Why in the world did I make this??
Soo, many laptops have ONLY 2 USB ports, but, this is not even close to enough for some people who need a lot of things connected to their computer at once. And anyways, who would want to repeatedly unplug stuff again and again everytime you need to use something and all of your laptop's USB ports are used (this can also damage your usb port)? I can tell you for sure that I would not want to. So I decided to make my USB hub, Easyhub (it makes connecting lots of devices to your laptop easier), it converts 1 USB port on your laptop (or computer) into a whopping 10 (this can be useful if you need to connect a lot of arduinos/esp32s'/etc at once)!

# How can this majestic device be used??
To use this, you simply just need to plug it into a computer's USB port and it converts that port into a whopping 10 ports! This can be great to connect many small devices into your computer (keyboards, mice, pheripherals) but, even if you connect it into a USB 3.0 port you will get USB 2.0 ports and if you have one of those billion dollar 1TB flash drives laying around, I would recommend plugging it directly into your computer's port unless you want reduced speeds.

# PCB and Schematic
<img width="806" height="576" alt="image" src="https://github.com/user-attachments/assets/41df90fa-c2a3-464f-91de-2d5d78899311" />
<img width="838" height="442" alt="image" src="https://github.com/user-attachments/assets/4813407f-a46f-4bcc-8250-4f86db62a482" />

# BOM (Also available in bom.csv)
 
 |Item|Price (total)|Link|
 |----|-------------|----|
 |SL2.1A|$4.13|https://www.lcsc.com/product-detail/C6798314.html|
 |AM90|$0.67|https://www.lcsc.com/product-detail/C404965.html|
 |AF SS-JB17.6|$2.60|https://www.lcsc.com/product-detail/C456021.html|
 |USB-231-ARY|$1.63|https://www.lcsc.com/product-detail/C720525.html|
 |CL10A106KP8NNNC|$0.65|https://www.lcsc.com/product-detail/C19702.html|
 |NSR0320MW2T1G|$0.63|https://www.lcsc.com/product-detail/C48192.html|
 
