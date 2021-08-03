# Welcome 
Hello! My name is Sabrirna Yepez. I am a 21 year old undergraduate senior at Embry-Riddle Areonautical University studying Electrical Engineering. Due to COVID-19, I decided to persue a Master's in Electrical and Computer Engineering degree until the job market stablizies itself. I have joined the accelerated master's program at Embry-Riddle Aeronatical University and have currently taken 3 graduate courses along side my undergraduate degree. It is my hope to find a fun fast-paced job in the central florida area, before my time as a college student expires. Although I still have a long ways to go in my career, it is my hope that this website will bring you up-to-date with my work so far.

## EagleCam

![image](https://user-images.githubusercontent.com/70720921/110346722-d57b1980-7ffd-11eb-99ab-fb81590506c2.png)


### About This Project

Project EagleCam will capture the first ever third person perspective of Intuitive Machines' Nova-C lunar lander desending on the lunar surface. With use of 802.11ac WiFi standards, EagleCam will create the first WiFi communication nextwork on the lunar surface. Our team is the first univeristy team to have a payload on the lunar surface, so we have partnered with many companies with previous mission experience to help us achieve our goals. Some of our partners include Intuitive Machines, NASA, Arrow, Aerojet Rocketdyne Foundation, and the Air Force research laboratory. To find out more about this project click [here.](https://daytonabeach.erau.edu/eaglecam)

![image](https://user-images.githubusercontent.com/70720921/110348126-4f5fd280-7fff-11eb-883d-19b17ec396f3.png)
![image](https://user-images.githubusercontent.com/70720921/110348213-656d9300-7fff-11eb-804f-fdb38cd17582.png)

EagleCam is composed of two CubeState structures: the Deployer and EagleCam modules. The Deployer module connects the Nova-C lunar lander to the EagleCam module. The deployer will work as our communication reciever and interface between the EagleCam module and the Nova-C. The EagleCam module will house the camera system and transmission antennas. On this project, I am developing the power and communication subsystems. 

### Power Subsystem

![image](https://user-images.githubusercontent.com/70720921/110350726-04938a00-8002-11eb-8783-83bce30593d1.png)
![image](https://user-images.githubusercontent.com/70720921/110350753-09583e00-8002-11eb-8b34-1e081399c6b4.png)


The power subsystem consists of two power conditioning PCBs designed on EAGLE (One on the Deployer module and one of the EagleCam module). The PCB designs are manufactured using the gerber files from EAGLE and imported onto an LPKF micromachining U4 laser. They are then assembled, tested, and integrated with the rest of the system.

### Communication Subsystem

![image](https://user-images.githubusercontent.com/70720921/110349561-d06b9980-8000-11eb-9d37-b33c7c666df5.png)
![image](https://user-images.githubusercontent.com/70720921/110349672-eaa57780-8000-11eb-84fe-846994480dae.png)

The communication subsystem consists of a WiFi module, 2 transmission antennas (EagleCam) and 4 receiving antennas (Deployer). Together they will transmit a series of images from the Deployer to the lander, then from the lander to the space station, then back to Earth. The antennas follow the IEEE 802.11ac standard functioning at 5.5 - 5.85 GHz range. I manufactured these antennas on the LPKF micromachining U4 laser, and tested them using a Keysight ENA Series Network Analyzer.

## Antenna Radiation Shielding

![image](https://user-images.githubusercontent.com/70720921/110351560-f5f9a280-8002-11eb-8a1a-d3181336e897.png)

Analyzed the radiation shielding effectiveness of a 3-D printed two-layer couple-fed microstrip antenna between a variety of materials.

![image](https://user-images.githubusercontent.com/70720921/110351662-10cc1700-8003-11eb-8e4b-0b94e2585eb7.png)

Above is our test set-up. By performing a low-cost radiation testing, we were able to quantify the  absorbed ionizing radiation of various sample materials under a 1 uCi radioactive disk of Cobalt-60. 

![image](https://user-images.githubusercontent.com/70720921/110529626-7b568300-80e7-11eb-9021-2153179aa241.png)

The Figure above shows our test results. It was found that Onyx, an additive manufacturing material, protects from ionizing radiation; therefore, it can be used for in-space antenna manufacturing. This information was submitted as a research paper to [IEEE WAMICON 2021](https://daytonabeach.erau.edu/eaglecam) conference.

## BotTender

![image](https://user-images.githubusercontent.com/70720921/110352942-808ed180-8004-11eb-833d-4dee10d521a2.png)

The botTender system is a kitchen appliance that will dispense a selection of cocktails, liquors, and non-alcoholic beverages. The system will store 6 bottles consisting of a variety of liquors, sprits, and mixers that will be used to dispense all beverages. Each bottle will have their own pump that will carry the liquid content inside the bottle to the front of the system for beverage dispensing. The user will be able to select from a variety of cocktails, shots, or custom drinks to be dispensed at the front end of the system where the user has been told to place their cup. 

![image](https://user-images.githubusercontent.com/70720921/110353247-d5324c80-8004-11eb-866b-a155734204f0.png)
![image](https://user-images.githubusercontent.com/70720921/110354028-ba140c80-8005-11eb-9d16-6bbd6a27bced.png)


This project is for the graduate Mechatronics course. In this system, my main responisbility was Electrical Hardware Design and Integration. I developed the system architecture above during the first week of product development. I had also developed the inital sketch of the system as a rouch outline for what the team needed to develop. Currently, the project is in its software development phase. I have been working with the software and controls team to create an embedded python system that will utilize an RFID scanner to read the NFC tags of each bottle and register them to a database. This database will then display all possible drink recipies for the user to select from and keep track of the available content inside each bottle.
