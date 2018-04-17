# CS207_Phone_Locator_And_Email_Using_Blynk
--------------------------------------------

The point of this repository is to explain how phone locator works and how to send email using Blynk. 

The project works really simply, whenever the user presses a button, The Arduino Uno will read the phone's geolocation and send the client an email.Another cool feature added  is that when a phone is lost or stolen, a phone owner can e-mail using blynk, so that the person can’t get the information which is stored in that phone. A response from the Arduino will be received in about 15-20 seconds from the press of the button if the phone is located.

**********************************************************************************************************************
This Picture is the set-up of Phone Locator and email using blynk:
----------------------------------------------------------------

![arduino uno_bb](https://user-images.githubusercontent.com/37346950/38885793-5c0b9f6e-4231-11e8-954d-40c0fafb2bed.jpg)



![df_schem](https://user-images.githubusercontent.com/37346950/38888536-27bc5b24-4239-11e8-9809-7a40fa1485b8.jpg)

















Repository Contents
--------------------
Here is my introduction  of this repository:

/src - All the software programs (.ino, C++, .java)

/hardware -  all 3D and other desgin model.

/build - Files which are good to run.

/libraries - libraries which are required in this program.

/examples - Example files.

/img - In this the image are stored. 

/LICENSE - The license file.

/README.md - The cuurent file.

***********************************************************************************************************************

Materials Required
-------------------

The following materials are required:

--- Arduino UNO 

--- Jumper wire 

--- Resistor 221 Ohms

--- Breadboard

--- Smart Phone 

--- SparkFun pushbutton switch 12mm

In addition, the user has to download a following software application in the phone

--- Blynk 

--- Arduino Web Editor 

**********************************************************************************************************************

Libraries
----------

1) Bridge - Arduino LLC this library is in the public domain.

2) Blynk - Blynk this library is released under the MIT Liscence.

Set-up
-------

1) Download Bylnk in your smartphone

2) create new project name as "Phone Locator".

![png image](https://user-images.githubusercontent.com/37346950/38886545-7f6fc104-4233-11e8-83f2-5681580f18ae.png)



![2018-04-17-photo-00000377](https://user-images.githubusercontent.com/37346950/38888999-8870adfc-423a-11e8-9ef8-1b7293098b00.jpg)




When button is pressed -----> Get the location 
      
                                     |
                                     | 
                                     |
                                     V
Send message and Email <------  Process the Data








1) if(button is pressed) will check if the button connected to pin 2 is pressed

2)getLocation will request the phone's location from Blynk

3)Process Data will process the received co-ordinates into the body of the email

4) Send email will send the email to the user


Credits
--------

I wanted to give  credit to  third parties where I borrowed from.

Andrei Florian - structure and idea

Trevor Thomesh - Explain and help me on API problem. 

A special Thank You to both of you to make this project successful.



