# Frozen Slimes 

### Contact: artemis#8615


## Check out the new discord server and chat with other people building some slimes! https://discord.gg/vhHEsKjWGV

This project will currently be using a Wemo D1 mini, mpu6050, and a TP4056 charger. On my personal slimes I use 18650 batteries and wanted a case that can fit these without being massive. [Offical Component Guide](https://docs.slimevr.dev/diy/components-guide.html)


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
- [Switch](https://docs.slimevr.dev/diy/components-guide.htmll)
    - [SS22F32](https://www.aliexpress.com/item/32975535599.html)
- [Battery](https://docs.slimevr.dev/diy/components-guide.html) (*804040 is what the docs suggest, I used 18650s as they will last for a solid 30 hours, I will have cases for each version eventualy*)
    - [18650](https://www.amazon.com/s?k=18650&crid=2H65KICLJGU4U&sprefix=18650%2Caps%2C301&ref=nb_sb_noss_1)
- [1n5817 Diode](https://www.amazon.com/100-Pieces-1N5817-Schottky-Rectifier/dp/B079KDQQPD/ref=sr_1_5?crid=1EPLYISD4R4G3&keywords=1n5817+Diode&qid=1659032765&sprefix=1n5817+diode%2Caps%2C130&sr=8-5)
- [180k Resistor](https://www.amazon.com/EDGELEC-Resistor-Tolerance-Resistance-Optional/dp/B07HDFCNXB/ref=sr_1_3?crid=9MPFJ93KJT6X&keywords=180k+resistor&qid=1659032821&sprefix=180k+%2Caps%2C129&sr=8-3)
- [M3 Insert](https://www.amazon.com/initeq-M3-0-5-Threaded-Inserts-Printing/dp/B077CL322T/ref=sxin_16_ac_d_mf_brs?ac_md=6-2-aW5pdGVx-ac_d_mf_brs_brs&content-id=amzn1.sym.715b40e5-7b73-447b-bbb7-382000b19785%3Aamzn1.sym.715b40e5-7b73-447b-bbb7-382000b19785&crid=3D6LG19044RU7&cv_ct_cx=m3+insert&keywords=m3+insert&pd_rd_i=B077CL322T&pd_rd_r=6a9928bf-8120-480c-b6e6-ac4a3efb5da3&pd_rd_w=Ci2YY&pd_rd_wg=EGaoL&pf_rd_p=715b40e5-7b73-447b-bbb7-382000b19785&pf_rd_r=BPZY01PVZZCHQVTXDYB9&psc=1&qid=1659033175&sprefix=m3+insert%2Caps%2C151&sr=1-3-dd96d2aa-78c0-4648-bd3e-11643d087866)
- [M3 hardware](https://www.amazon.com/DYWISHKEY-Pieces-Socket-Screws-Wrench/dp/B07VRC5RJ8/ref=sr_1_13?crid=RON51NO1L8L7&keywords=m3+hardware&qid=1659033217&s=hi&sprefix=m3+hardware%2Ctools%2C115&sr=1-13)


### Case

![179154118-54a93cc8-1396-49c0-82b8-989af2cbaeec](https://user-images.githubusercontent.com/98719680/227734713-58f0decb-38d4-4aa8-9286-1f77ffbb351c.jpg)


Stls and Fs3d files will be avilable soon!



### PCB 
This PCB lets every component be soldered on without any extra wires. This includes the diodes and resistor for battery sense and protected charging.  
![151724886-2c5099e3-fb9f-46b9-8021-25dd6d12512c](https://user-images.githubusercontent.com/98719680/227734726-2b1583f2-802d-49e9-b209-765abb201bdc.png)

![151725786-9f9a4075-871c-4021-ad3d-9da2e22d66e9](https://user-images.githubusercontent.com/98719680/227734730-0502b22f-1bf0-4fee-b222-e79eb37a7a76.png)

The gerber file for this is labled ``` frozen slime gerber file v1 ```
![179153864-273dd1f5-f176-403c-97f8-0ed151fe021a](https://user-images.githubusercontent.com/98719680/227734744-438f7aa4-5166-41e5-9350-1b442b70dafe.jpg)


- Top left pads are for battery

- Switch pads are for switch, wiring direction does not matter

- Final four pads are for soldering an extension

*may make solder pads smaller on future versions*

To order PCBS go to a website like https://cart.jlcpcb.com/quote upload the gerber file and select quanity and color and order. It should autoselect all the other correct options when you upload the gerber file. 


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

- [ ] Add 180K resitor and diodes in the same orientation as the picture 

- [ ] Set PCB inside the case (You may need to cut the pins down on the backof the pcb)
- [ ] Slide switch though front of case and solder to PCB
- [ ] Add wires to battery and solder to + and - on PCB 
(People panic about soldering lions because heating up the battery can shorten lifespan and cause failure. Roughing up the contacts with sandpaper and throwing some score marks in the contacts can make solder stick easier. 
I just get a blob of solder on the tip of my iron (800f) and set it on the battery. Then just touch the iron to it and set the wire inside. If you have to try for more then around 15 seconds just set it aside and work on another battery. This can be kind of tricky for the first time but people stress more then really needed.)

- [ ] Add M3 insert into plastic. I recomend putting insert on a M3 screw on a hex key and heating with a lighter for 5 to 7 seconds depending on flimanet used. Slide insert from inside of case to the outside 
![179158043-c3d5d297-a795-4f47-a854-b419975b66b6](https://user-images.githubusercontent.com/98719680/227734763-53320ba5-9987-46ab-998f-02493e345269.jpg)

![179157821-9063bb6c-d6fe-42cc-9a80-24e61e10c817](https://user-images.githubusercontent.com/98719680/227734775-b4eba9c5-0f17-4ed9-a3d7-80ebbb0ccb63.jpg)


- [ ] Feel free to reach out to me with any questions 



### Links
Resources:
- [The Docs (SlimeVR Documentation)](https://docs.slimevr.dev/)
- [Github Repository SlimeVR](https://github.com/SlimeVR/)
- [SlimeVR Discord](https://discord.gg/SlimeVR)



