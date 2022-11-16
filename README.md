# Smart-Building
IoT system in an office setting

## Project Overview

### Smart home
IoT features include:

#### Automation
* A gate with RFID chip and a car with a card to open and close automatically when the owner's car approaches it.
* Rooms with ultrasonic sensors to detect the presence of people and turn lights and fans on and off.
* Doors with servo motors and ultrasonic sensors to open and close doors when people approach them.
* Temperature sensor to read temperature and humidity of rooms.

#### Customization
A living room with modes to suite the owner's immediate needs.

###### Modes include:
* Meeting mode with bright lighting and option for projection to turn off all lights and display 'Do not Disturb ' message on the door.
* Party mode with lights off, a disco bulb implemented with LEDs and music.
* Study mode with bright lighting and option for music.

#### Perimeter security
* A fence with motion sensor to turn on the lights when motion is detected within a certain range.
* Fence with barbed wire connected to touch pins on the esp32 to trigger an alarm system; implemented with a buzzer when contact is made.

#### Networking
All components of the house connected to a web app so the owner can control devices remotely.

#### Safety
All systems connected to a single relay to turn off all power in case of an emergency.


#### Components
* Breadboards
* USB cable
* Jumper cables
* Dupont Wires
* Cables 
* Esp32 microcontrollers
* Power Supply Module
* RFID chip and card
* DHT-11 (temperature and humidity sensor)
* Ultrasonic sensors
* PIR sensors (Motion sensor)
* Servo motors
* Relays
* Active buzzer
* Fan
* LCD1602 module (display board)
* LEDs
* Resistors



### Conversion To Smart Office

#### Why? What? Who?

##### Questions defining goal
* What is the problem?
* Who has this problem, and what do we know about them?
* What are their concerns and needs?
* How do they interact with their environment?
* How do they influence their environment?
* What causes this problem?
* When does this problem occur?

##### Answers
* Cost of power consumption and maintenance of appliances is too high.
* Company leaders, they are willing to invest in anything that cuts costs, work force or is beneficial for their organisations in the long run.
* They need an easily-accessible automated system for their buildings, they worry about their employees' privacy and well-being and they'd also like to cut down costs.
* They have meetings scheduled throughout the day and sometimes work overnight.
* They introduce a lot of carbon emmissions and other harmful substances into the environment.
* Employees often neglect to turn off utilities when not in use.
* Mostly at night when the work requirements are completed.


#### Design Thinking
* Available solutions to same problem or similar
* Pros and cons of available solution
* Cost of existing solution
* Level of relevance, innovation and/or disruptiveness
* Limits of existing solution


#### Features
* Lighting
* Air conditioning and ventilation
* Doors
* ...


#### General Challenges
* Microcontrollers to use
* Sensors to use
* Relevant actuators
* Heirachy of processors
* Interdevice communication protocols
* Wired or wireless communication (LoRa, Bluetooth, WiFi)
* Cost
* Security
* Optimization
* Time
* Communication


#### Skills needed
* 3D printing.
* Web/app development.
* Electrical engineering
* Artificial intelligence


#### Sections of The Project
* General research
* Hardware
* Software


##### General Research
* Existing Solutions
* Security & Privacy
* Wireless networks
* Compatibility 
* Cloud computing
* Commercialization
* Communication protocols


##### Hardware
* Circuitry
* Simulations
* Sensors
* Actuators
* Microcontrollers
* Microprocessors


##### Software
* Artificial Intelligence
* Micro Compatibility
* Operating System
* Libraries
* Programming Languages



#### Delegation of Duties
* Aliyu - Research on wireless networks, hardware 
* Ire - Documentation
* Timi - Research on Material resources
* Keside - Research 
* Ebube - Hardware team lead, software (ML)
* Ade - Software
* Ugbana - Software
* Dolapo - Hardware
* Aliyu - Hardware
* Mr. Victor - Tips and ideas
* Mr. Tolu - Project management, hardware



##### Conclusions (30-08-2022)
* Lobby with spy cam coupled with geographical positions to open doors externally based on human presence/proximity.
* Spy cams turn on (close circuit) for rooms with humans.
* Ultrasonic sensors to control internal functions (for now ~because of the cost of spy cams).
* One HC per room and one spy cam for the lobby.
* Arduino as main controller and esp32 as peripherals.
* Raspberry Pi and Arduino for the above functions in the second stage.
* End-to-end encrypted transmission of data from spy cams to assure user privacy.



###### What do you consider as key factors of success?
