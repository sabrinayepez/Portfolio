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

### About This Project

With the revival of the space industry following the rise and sucess of Space-X, private companies have been interested in the buisness opportunities that lie in deep space exploration, primarily mining mineral resources. Additive manufacturing in-space (IMS) plays an essential role in long-term exploration mission sustainability based on on-demand production and recyclability materials. However, the interaction of charged particles on materials affects the materials’ mechanical properties when exposed to the radiation environment of space for long periods of time. This project focuses on the effectiveness of radiation shielding of a 3D-printed ABS sample and a 3D-printed carbon fiber filled nylon composite sample for short-time exposure. Since carbon fiber filled nylon composite has better shielding effectiveness, a two-layer coupled-fed 3D-printed microstrip antenna is presented for antenna-on-package applications, where the antenna itself can be used as a shielding element. The goal is to prove the duality of this 3D printed sample as a fully functioning antenna as well as a protective layer of the system for deep space exploration.

### Radiation Testing

![image](https://user-images.githubusercontent.com/70720921/110529626-7b568300-80e7-11eb-9021-2153179aa241.png)

For this project, I worked on analyzing the radiation shielding effectiveness of a 3-D printed two-layer couple-fed microstrip antenna between a variety of materials. Above is our test set-up for analyzing absorded ionizing ratiation. By performing a low-cost radiation testing, we were able to quantify the absorbed ionizing radiation of various sample materials under a 1 uCi radioactive disk of Cobalt-60. 

<img width="248" alt="Screen Shot 2021-10-08 at 1 26 30 PM" src="https://user-images.githubusercontent.com/70720921/136598339-79e433c4-96b7-469b-823a-2618bfc7f1b0.png">

The Figure above shows our test results. It was found that effectiveness of the radiation shielding for ABS is 13.57 %, while Onyx is 17.63 %. Therefore, proving Onyx is the most protective from ionizing radiation and can be used for in-space antenna manufacturing. This information was submitted as a research paper to [IEEE WAMICON 2021](https://daytonabeach.erau.edu/eaglecam) conference.

## BotTender

<img width="735" alt="Screen Shot 2021-10-08 at 1 39 50 PM" src="https://user-images.githubusercontent.com/70720921/136599813-59ee3894-ec40-4e01-9a02-b80328b0f1e6.png">


### About This Project

The botTender system is a kitchen appliance that will dispense a selection of cocktails, liquors, and non-alcoholic beverages. The system will store 6 bottles consisting of a variety of liquors, sprits, and mixers that will be used to dispense all beverages. Each bottle will have their own pump that will carry the liquid content inside the bottle to the front of the system for beverage dispensing. The user will be able to select from a variety of cocktails, shots, or custom drinks to be dispensed at the front end of the system where the user has been told to place their cup. 

### Hardware Design and Integration 

<img width="862" alt="Screen Shot 2021-10-08 at 1 44 17 PM" src="https://user-images.githubusercontent.com/70720921/136600332-6cd511d3-7277-4b33-ac90-4ca4d70a9213.png">

This project is for the graduate Mechatronics course. In this system, my main responisbility was Electrical Hardware Design and Integration. I developed the system architecture above during the first week of product development. I had also developed the inital sketch of the system as a rouch outline for what the team needed to develop. The system would function with 2 computing systems (an Arduino and Raspberri Pi) each running their respective systems and communicating over serial connection. 

<img width="787" alt="Screen Shot 2021-10-08 at 2 03 22 PM" src="https://user-images.githubusercontent.com/70720921/136605277-1bf17f68-b62d-4fbb-be91-68b4aaff0419.png">

The Raspberry Pi was used as the User Interface (UI) of the system. Above is the UI layout of the Python program used in this project. The Raspberry Pi was connected to a touch-screen display which allowed the user to naviage through the various pages of the UI. The UI consisted of a home menu, help page, user profile, custom drink menu, and cocktail menu. The system always started in the home menu where the user could select which of the 4 pages they would like to be directed to. The help menu presented the user with the user manual and troubleshooting tips. The user profile allowed the user to see their previous selected drinks and change the color of the LED lights on the system. The custom drink menu allowed users to create their own drink from their current inventory and the cocktail menu allowed users to select a preset drink recipe from the database that it could produce from its inventory. The Raspberry Pi got information of the current inventory through a serial connection from Arduino (further explained below). 

<img width="461" alt="Screen Shot 2021-10-08 at 1 47 16 PM" src="https://user-images.githubusercontent.com/70720921/136600646-3965bd9f-f089-454c-9603-b580f98ba260.png">
<img width="478" alt="Screen Shot 2021-10-08 at 2 01 57 PM" src="https://user-images.githubusercontent.com/70720921/136605153-e80c117a-d79c-4427-9eb7-bed33d569545.png">

The Arduino was used to run the RFID bottle and cup detection of the system and activate the pumps to dispense the drinks. Six of the RFID readers were used to read the NFC tag on the bottom of the inventory bottle using the layout above and tie these valies to its pump location. The NFC tags on these bottles held information as to what liquid was stored inside them. The last RFID scanner was located underneath the dispensing area of the device. The NFC tag of the dispensing cups held information on the size of the drink needed to be dispensed. Through experimental testing we were able to identify the time constants of each pump to pour 1oz of liquid. After recieving a serial message from the Raspberry Pi with the ratio of ingredients needed for the desired drink, the Audino would calculate how long to activate the pumps of the required liquids to dispense the right amount into the cup located at the front of the device. 

![image](https://user-images.githubusercontent.com/70720921/110352942-808ed180-8004-11eb-833d-4dee10d521a2.png)
<img width="814" alt="Screen Shot 2021-10-08 at 2 14 59 PM" src="https://user-images.githubusercontent.com/70720921/136604869-36edc764-d8f6-42ec-a6ee-38b19029559f.png">

The final step of the project was to place all the electrical components inside the housing of the device. The housing was modeled using AutoCAD and was 3D printed using ADS. The electrical components, except the pumps and touch display, were placed at the base of the housing with wires running through the center support pillar to the top of the housing where the pumps and touch-display were located. 
