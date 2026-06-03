**May 23:**

I added loaded all the major componants of the PCB into KICAD.
 - ESP32 Devkit
 - MPU6050
 - 2x buttions
 - Power switch
 - Pins

I started planning the connections between the MPU and ESP32 and started making little notes about what I want this to do.

*Time spent: 1hr*

**May 29:**

I finshed most of the scamatic. 
I decided that I want to use an MPU6050 breakout module instead of having it on the PCB. 
I added 4x leds (one for each corner of the PCB) and a passive buzzer to declair if your guess was correct or not. 

I think in the morning I'll look at it 1x more before I switch to the PCB editor. 

*Time spent: 1.5hrs*

**May 31:**

I messed up the roughting for the LEDs so I edited it a bit but I think I'll re-do it agin when I organiz everything in the PCB editor. 

I also needed to double check the order of the MPU pins (I am soldering on an external module into holes on my PCB) I want the module to lay on the bored and not hang off of it so I needed to make sure that when I soldered it on it would be in the right configureation. If I mess it up I'll just solder it on the back but I'd rather it be on the front.

<img width="677" height="465" alt="image" src="https://github.com/user-attachments/assets/7614717d-417c-44b4-88a7-361f998e3c4c" />
(Isn't it so pretty :)

I am now ready to move onto the PCB editor :)

*Time spent: 30-45min*

**6/3**

I assingned all my parts footprints and realized that it would be much better for this project if I used an ESP32-S3 bored and not the chip that I was useing. I took out the chip and added 2 pin socket headders so i could plug in my esp32. 

I had to do alot of rescerch on the diffrent parts/footrpints (I am still learning) but I am relatively confident that they are the best fit for the project. 

Updated Scamatic: 

<img width="683" height="463" alt="Screenshot 2026-06-03 071840" src="https://github.com/user-attachments/assets/8c6f0ae2-1316-4c42-a05b-a6010f173ba8" />

Footprints:

<img width="788.5" height="450.5" alt="Screenshot 2026-06-03 071107" src="https://github.com/user-attachments/assets/810725de-7981-4c6c-9265-3b13bc0d2244" />

*Time Spent: 1hr*
