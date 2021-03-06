# Frozen Slimes 

## Hi everyone, this is a slime vr project to create slime tracker cases that are similar to the official cases but fit all the diy components.

## This is a work in progress, PCBS have been tested and do work, cases have been tested but are still being refined. 

### Contact: lynxo#7417

This project will currently be using a Wemo D1 mini, mpu6050, and a TP4056 charger. On my personal slimes I use 18650 batteries and wanted a case that can fit these with out being massive. [Offical Component Guide](https://docs.slimevr.dev/diy/components-guide.html)


## Index
- [Components](#Components)
- [Case](#Case)
- [PCB](#PCB)
- [Printing](#Printing)
- [Assembly](#Assembly)
- [Links](#Links)


### Components

    
- [TP4056](https://www.amazon.com/HiLetgo-Lithium-Battery-Charging-Protect/dp/B00LTQU2RK/ref=sr_1_3?crid=31BCDZYQGA5IU&keywords=TP4056&qid=1643591253&sprefix=tp4056%2Caps%2C124&sr=8-3)
- [Wemos D1 Mini](https://www.amazon.com/Organizer-ESP8266-Internet-Development-Compatible/dp/B081PX9YFV/ref=sr_1_3?crid=2FMF3NVYGOSPK&keywords=wemos+d1+mini&qid=1643591309&sprefix=wemos+d1+mini%2Caps%2C136&sr=8-3)
- [40mm straps] made these from elastic and velcro
- [IMU docs](https://docs.slimevr.dev/diy/components-guide.html)
    - [MPU6050](https://www.amazon.com/MPU-6050-Accelerometer-Gyroscope-Converter-Compatible/dp/B08TH9NH55/ref=sr_1_6?crid=1W65V3QJ27XN&keywords=mpu+6050&qid=1643591376&sprefix=mpu+6050%2Caps%2C136&sr=8-6)  
- [Switch](https://docs.slimevr.dev/diy/components-guide.htmll) (*SS22F32 is what the docs suggest, this rocker is what this case is designed for*)
    - [rocker](https://www.amazon.com/dp/B01N2U8PK0?psc=1&ref=ppx_yo2_dt_b_product_details)
    - [SS22F32](https://www.aliexpress.com/item/32975535599.html)
- [Battery](https://docs.slimevr.dev/diy/components-guide.html) (*804040 is what the docs suggest, I used 18650s as they will last for a solid 30 hours, I will have cases for each version eventualy*)
    - [18650](https://www.amazon.com/flashlights-Rechargable-universal-zoomable-resistant/dp/B089N1HS3Y/ref=sr_1_7?keywords=18650&qid=1643591647&sr=8-7)
    - [804040](https://www.aliexpress.com/item/33021202630.html)
    - [503759](https://www.aliexpress.com/item/1005003257130562.html)


### Case

![IMG_5092](https://user-images.githubusercontent.com/98719680/179154118-54a93cc8-1396-49c0-82b8-989af2cbaeec.jpg)

Stls and Fs3d files will be avilable soon!



### PCB 
This PCB lets every component be soldered on without any extra wires. This includes the diodes and resistor for battery sense and protected charging.  
![pcb](https://user-images.githubusercontent.com/98719680/151724886-2c5099e3-fb9f-46b9-8021-25dd6d12512c.png)


![unknown](https://user-images.githubusercontent.com/98719680/151725786-9f9a4075-871c-4021-ad3d-9da2e22d66e9.png)

The gerber file for this is labled ``` frozen slime gerber file v1 ```
![IMG_5080](https://user-images.githubusercontent.com/98719680/179153864-273dd1f5-f176-403c-97f8-0ed151fe021a.jpg)

- Top left pads are for battery

- Switch pads are for switch, wiring direction does not matter

- Final four pads are for soldering an extension

*may make solder pads smaller on future versions*


*if you want to buy pcb packs, fully assembled pcbs or even whole trackers dm me*


### Printing 
Tips
- Smaller layer height will make the prints come out higher quality (duh). 
- I like to print the lid vertically with the only flat surface on the bed so that the margins around the battery are extreamlly exact so the battery dosent rattle. 

### Assembly 
Steps 
- [ ] Print main tracker case
- [ ] Print lid 
- [ ] Print cap 

- [ ] Solder charge board to PCB
- [ ] Solder mpu to PCB 
- [ ] Solder pins from wemo D1 to wemo, set through holes on PCB and solder the pins on the backside of the PCB

- [ ] TODO add instructions for diodes 

- [ ] Set PCB inside the case 
- [ ] Slide switch though front of case and solder to PCB
- [ ] Add wires to battery and solder to + and - on PCB

- [ ] Add M3 insert into plastic. I recomend putting insert on a M3 screw on a hex key and heating with a lighter for 5 to 7 seconds depending on flimanet used. Slide insert from inside of case to the outside 
![IMG_6932 1](https://user-images.githubusercontent.com/98719680/179158043-c3d5d297-a795-4f47-a854-b419975b66b6.jpg)

![IMG_6936](https://user-images.githubusercontent.com/98719680/179157821-9063bb6c-d6fe-42cc-9a80-24e61e10c817.jpg)

![IMG_6934](https://user-images.githubusercontent.com/98719680/179157832-a3ff8dd8-6f05-40e3-854c-6d48003c82ad.jpg)

- [ ] Feel free to reach out to me with any questions 



### Links
Resources:
- [The Docs (SlimeVR Documentation)](https://docs.slimevr.dev/)
- [Github Repository SlimeVR](https://github.com/SlimeVR/)
- [SlimeVR Discord](https://discord.gg/SlimeVR)





```

- [TP4056](https://www.aliexpress.com/item/32649780468.html)
- [Wemos D1 Mini](https://www.aliexpress.com/wholesale?SearchText=D1+mini)
- [40mm straps](https://www.aliexpress.com/item/1005002350231996.html)
- [IMU](https://docs.slimevr.dev/components-guide.html) (*BNO08x chips are currently in a pretty bad shortage*)
    - [MPU6050](https://www.aliexpress.com/wholesale?SearchText=MPU6050)  
- [Switch](https://docs.slimevr.dev/components-guide.html) (*SS22F32 is what the docs suggest, SS12D00G3 is smaller and looks better for this case*)
    - [SS12D00G3](https://www.aliexpress.com/wholesale?SearchText=SS12D00G3)
    - [SS22F32](https://www.aliexpress.com/item/32975535599.html)
- [Battery](https://docs.slimevr.dev/components-guide.html) (*804040 is what the docs suggest, 503759 is smaller and usually higher capacity*)
    - [804040](https://www.aliexpress.com/item/33021202630.html)
    - [503759](https://www.aliexpress.com/item/1005003257130562.html)
    
    ```
