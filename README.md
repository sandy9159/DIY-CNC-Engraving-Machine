# DIY-CNC-Engraving-Machine

![image](https://user-images.githubusercontent.com/19898602/134300108-715eb08a-802b-4d2d-b99b-3bbcfba7e046.png)


Hello friends in this post I’ll show how I made my own mini DIY CNC engraving cum Milling machine using Arduino and GRBL CNC shield.

The frame of machine is made up of 12mm plywood which is very strong and easy to work with.


I have used 500W spindle for this mini cnc engraving machine which have enough power to work done.


working area of this machine is 120 x 120 x 30 mm.
I have tested this machine on Acrylic sheet, PCB, Wood and works fine.


I have not tested with aluminium yet, but yes for shaloow engraving with high quality end mill surely we achieve good result on aluminium as well.

So let see further in this post how to build this mini powerful diy cnc engraving machine.


# Video

lease watch the video complete I have display all construction details in the video

https://youtu.be/EcmxOMBsX7A


# Material Required

> Arduino UNO 1nos. 

> GRBL CNC Shield 1nos. 


> A4988 driver 4nos. 


> Nema 17 stepper motor 3nos. 


> 5mm to 8mm coupling 3nos. 


> 8mm SS smooth Rod 240mm 4nos. 


> 8mm SS smooth Rod 130mm 2nos. 


> T8 Lead screw 240mm 2nos. 


> T8 Lead screw 130mm 1nos. 


> Lead screw nut T8 3nos.


> Flange bearing 8mm 3nos. 


> shaft holder SHF8 8mm 12nos. 


> 8mm Linear bearing SC8UU 8nos.


> 8mm Linear bearing SCL8UU 2nos Aliexpress


> 12mm Plywood 15Sqft


> M4 & M5 nut bolts


> 165 x 120 6mm Acrylic sheet 1nos.


> 500W spindle complete set 1nos. 


> 24V DC 8Amps SMPS 1nos. 


# Frame Construction

![image](https://user-images.githubusercontent.com/19898602/134300642-e0c9838b-4755-45e0-9bcb-395dab6ae52d.png)

Download the CNC machine dimensions CAD file from below

https://drive.google.com/file/d/14fcUK3AHJ8QV08C6r4krWRHbJU7NJvqe/view?usp=sharing

All the dimension related to machine is mention in cad file its scaled to ratio 1:1 you can directly print is and cut past on plywood for easy cutting of parts.

![image](https://user-images.githubusercontent.com/19898602/134300714-b718149b-c958-47a7-9eda-1fef9ad8c697.png)


Here I am cutting a 12mm plywood using jigsaw machine to make the frame of CNC machine.
I am using wood because it is enough strong for this purpose also it is light weight and easy to cut and making holes.

![image](https://user-images.githubusercontent.com/19898602/134300771-ff94fef9-5f27-41b4-9346-4882ae9526b4.png)
![image](https://user-images.githubusercontent.com/19898602/134300797-5798dedb-c25a-4201-882b-9fd889966796.png)


I have marked the holes location on plywood and making hole using a vertical drill machine I have use 25mm drill bit to make hole for stepper motor.

![image](https://user-images.githubusercontent.com/19898602/134300853-31ac1f08-7ff7-446a-9662-ab20494ac960.png)

After cutting and drilling holes on 12mm plywood I clamp it on right angle clamps to make drill screw on the edges. in this way our basic frame is ready.

![image](https://user-images.githubusercontent.com/19898602/134300904-841aa339-46be-4f5b-aca7-7cc93255f4f9.png)


![image](https://user-images.githubusercontent.com/19898602/134300940-7d19ddbf-21df-42a3-81c0-f2ddadbe7dac.png)![image](https://user-images.githubusercontent.com/19898602/134300962-54735c1c-8876-4296-8d8c-9d983bd015a4.png)


Here I use 240mm of 8mm smooth rod and 8mm 240mm Lead screw details
Linear bearing and shaft holder quantity is avail at material required section.

![image](https://user-images.githubusercontent.com/19898602/134300999-da12f097-bcee-48ce-8d59-62855fbd4831.png)


Here I installed the Z axis also

![image](https://user-images.githubusercontent.com/19898602/134301054-23591a73-d86a-4919-9198-08dc0cda30ce.png)
![image](https://user-images.githubusercontent.com/19898602/134301071-9e1fe6f8-4213-41e2-914d-064f332de8ff.png)

This 500W spindle motor this is very silent in operation and powerful at same time, 

this spindle kit came with all necessary components like 52mm spindle clamp ER11 Collet and wide range of collet chuck 1mm to 6mm power supply etc.





## Wiring details of CNC engraving machine

![image](https://user-images.githubusercontent.com/19898602/134301174-fc89ef48-c8a6-4df6-8a03-82d25fe3d740.png)

I have design circuit and PCB in [easyEDA](https://easyeda.com/) and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly. they now also have PURPLE colour PCB option also without any extra cost
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get 18$ welcome coupon from [JLCPCB](https://jlcpcb.com/IAT ).


![MVI_0001 00_06_45_21 Still003](https://user-images.githubusercontent.com/19898602/133377296-ba24f45e-dcf4-4f97-9aa5-77aaed90175a.jpg)
![image](https://user-images.githubusercontent.com/19898602/134336506-1f9b024e-41d9-47e0-82af-bd4c066cc060.png)



## GRBL Firmware

In this Machine I used GRBL firmware

![image](https://user-images.githubusercontent.com/19898602/134301320-4d347b1f-5210-40e4-b54f-c0de5bcac514.png)


## 3D CAD CAM Software

I have used Fusion 360 for 3D design and tool path generation

![image](https://user-images.githubusercontent.com/19898602/134301368-df2ed908-5bc6-4da2-967b-78839c7ee451.png)


Watch this video to know how to generate Tool path and G-code for this CNC machine in fusion 360

https://youtu.be/t_du4W0qNrw

## G Code sender

![image](https://user-images.githubusercontent.com/19898602/134301433-dcaa0dc6-7de1-4b1d-8928-044a06feff50.png)




![yt5s com-Arduino   TIP122 DC motor control _ 755 DC motor(720p)_1](https://user-images.githubusercontent.com/19898602/134301858-de0ed1d5-e17c-4ed2-b97f-349f0bc58984.gif)





