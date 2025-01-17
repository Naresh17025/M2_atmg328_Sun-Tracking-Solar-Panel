# OBJECTIVE OF THIS PROJECT :
Solar trackers are used to keep solar collectors/panels aligned with the sun as it moves around the sky every day. Solar Trackers improve the energy output of the heat/electricity generated by increasing the amount of solar energy received by the solar energy collector
# INTRODUCTION 
As nonrenewable energy supplies become scarcer, renewable energy sources are increasingly used to generate electricity. Solar panels are getting increasingly popular.We've already read an article on how to set up solar panels at home. A solar panel gathers solar energy, converts it to electrical energy, and then stores it in a battery.
This energy can be used as needed or as a straight replacement for grid-supplied electricity. The applications that make use of the energy stored in batteries are listed below.
Because of the Earth's rotation, the Sun's location in relation to the solar panel is not fixed. Solar panels should absorb as much energy as possible in order to make the most efficient use of solar energy.
This is only possible if the panels are always pointing in the direction of the Sun. As a result, the solar panel should revolve towards the direction of the Sun at all times. The circuit that rotates a solar panel is described in this article.
# PRINCIPLE OF SUN TRACKING PANEL
* Two LDRs, a solar panel, a servo motor, and an ATmega328 Microcontroller make up the Sun tracking solar panel.
* On the solar panel's edges, two light-dependent resistors are positioned. 
* When light falls on a light dependent resistor, it produces a low resistance. 
* The panel is rotated in the direction of the Sun by a servo motor connected to it. 
* The panel is set up in such a way that the light from two LDRs is compared, and the panel is rotated towards the LDR with the highest intensity, i.e. the least resistance. 
* The panel is rotated at a specific angle using a servo motor.
* When the light intensity on the right LDR is higher, the panel slowly travels to the right, and when the light intensity on the left LDR is higher, the panel gently goes to the left. 
* The sun is ahead at noon, and the intensity of light on both panels is the same. 
* In such circumstances, the panel remains stationary and does not rotate.
# CATEGORY
1.Monocrystalline (or single-crystalline) solar panels and polycrystalline (or multi-crystalline) solar panels are the two basic types of solar panels. 2.Monocrystalline solar panels, also known as single-crystalline panels, are the most advanced type of solar panels.
# COMPONENTS AND SUPPLIES
* Solar panel
* ATmega328 Micro Controller
* Light Dependent Resistor (LDR) x 2
* 10KΩ x 3
* Servo Motor
* 16MHz Crystal
* 22pF Ceramic Capacitors x 2
* Connecting Wires
# AUTOMATED SUN TRACKING SOLAR PANEL CIRCUIT DESIGN
The ATmega328 microcontroller, solar panel, light dependent resistors, and servo motor are all part of the proposed system.
# ATMEGA328 MICROCONTROLLER
The ATmega328 is a microcontroller from the AVR family. It's built on a cutting-edge RISC architecture. It's a controller with an 8-bit resolution. There are 32K bytes of Programmable Flash memory, 1K bytes of EEPROM, and 2K bytes of SRAM in this device. There are 23 programmable I/O pins on this board. Two 8-bit timers, one 16-bit timer, 6 channel ADC with 10-bit precision, programmable USART, Serial Peripheral Interface, 2 wire serial interface (I2C), and other peripheral functions are supported.
# SOLAR PANEL
The solar panel is mounted on a piece of cardboard (for demonstration purposes only), with the bottom of the cardboard linked to the servo motor. A solar panel is made up of photovoltaic cells that are placed in a certain arrangement. A solar cell is the same as a photovoltaic cell. The semiconductor substance silicon is used to make solar cells.
When a beam of light from the Sun strikes the solar cell, it absorbs a little quantity of energy. The absorbed energy is sufficient for electrons inside the atom to leap from one orbit to the next. The electrons in cells are directed by one or more electric fields, which produce current. These cells may be used to generate energy by putting metal contacts on them.
# LDR
LDRs (Light Dependent Resistors) are resistors whose resistance levels are proportional to the intensity of the light. The resistance value falls as the intensity of light shining on the LDR rises. LDR has the most resistance in the dark. The LDR will produce an analogue value that must be converted to a digital value. This may be accomplished with the help of an analogue to digital converter.
Internally, the ATmega328 features an analogue to digital converter. ADC0 to ADC5 (Pins 23–28) are the six ADC channels. Individual 10K resistors are used to link the two LDRs to ADC pins 27 and 28 in a voltage divider arrangement. The sequential approximation approach is used to convert ADC.
# SERVO MOTOR
The panel is rotated by a servo motor. A PWM signal must be sent to the servo motor's control pin in order to operate it, therefore Pin 17 (which contains PWM) is linked to the servo motor's control pin.
You may store the energy created by the solar cells by attaching a battery to the solar panel, and then utilise it when needed. Separate charge controller circuits are dedicated to efficiently controlling and charging the charge obtained from solar panels.
# ADVANTAGES OF SUN TRACKING SOLAR PANEL
* Because solar energy is a nonrenewable resource, it may be utilised.
* This also saves money because you won't have to pay for the energy you consume (excluding the initial setup cost)
* By watching the sun continually, it aids in optimum solar energy absorption.
# DISADVANTAGES OF SUN TRACKING SOLAR PANEL
* Because solar trackers are sophisticated systems with moving elements, they are slightly more expensive than their stationary counterparts.
* Trackers need greater upkeep than stationary systems. The amount and frequency of maintenance depends on the kind and quality of solar tracking system.
* Every tracking system necessitates extensive site preparation. Additional trenching and grading are also necessary for wiring and grading.
* From the perspective of a lender, financing monitoring initiatives is a more sophisticated and high-risk investment.
* Solar trackers are only suitable for warmer regions and are not suitable for snowy conditions. In comparison, fixed systems are more weather resistant than   tracking systems.
* Fixed tracking systems can support up to 20% slopes in the E/W direction and are field compatible. In the N/S direction, tracking systems typically bear less slope accommodation, usually approximately 10%.
# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL2 | SERVO MOTOR INTERFACING | IMPLEMENTED |
# LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1-LL1 | ABLE TO DETECT THE INTENSITY OF LIGHT WITH LDR | IMPLEMENTED |
| HL1-LL2 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL2-LL1 | LDR1>LDR2 ITS ROTATE RIGHT & LDR2>LDR1 ITS ROTATE LEFT | IMPLEMENTED |
| HL2-LL2 | SERVO MOTOR ROTATES THE PANNEL POSITION | IMPLEMENTED |
# LIMITATIONS OF SUN TRACKING SOLAR PANEL CIRCUIT
* Even while solar energy may be used to its full potential, it may cause complications during the wet season.
* Although solar energy may be stored in batteries, they are heavy, take up more room, and must be replaced on a regular basis.
* They're not cheap.
## SWOT ANALYSIS
# STRENGTH
* Low Maintenance
* Much Avaliable Space For Putting Up PhotoVoltaics
* Renewable Energy Resources
* Rich Solar Resources
# WEAKNESSES
* Small Scale Of Renewable Energy Of Economy
* Produces Direct Current
* Expensive
# OPPORTUNITIES
* Great Long Term Potential
* Increase Worldwide Awareness Of Climatic Change
* Increasing Gap Between Energy Supply And Demand
# THREATS
* Discontiunity of Energy Policies
* Dominnt Position Of The Fossil Fuels
# flowchart
![flowchart](https://github.com/Naresh17025/M2_atmg328_Sun-Tracking-Solar-Panel/blob/main/2_Architecture/flowchat.drawio.png)
# CIRCUIT DIAGRAM
![Sun-Tracking-Solar-Panel-Circuit-Diagram](https://user-images.githubusercontent.com/101312396/164251932-10d0d3db-7076-4061-baca-4cacf1615210.png)
# BLOCK DIAGRAM
![BLOCK DIAGRAM](https://github.com/Naresh17025/M2_atmega328_Sun_Tracking_Solar_Panel/blob/main/2_Architecture/Block%20diagram.drawio.png)
# Data Flow Transistion
![Data Flow Diagram](https://github.com/Naresh17025/M2_atmega328_Sun_Tracking_Solar_Panel/blob/main/2_Architecture/Data%20Flow%20Transistion.drawio.png)
# SCHEMATIC DIAGRAM
![schematic diagram](https://user-images.githubusercontent.com/101312396/164612420-d0954bc9-9fd1-4016-8e87-00b9203e9ee4.png)
## OUTPUTS
* OFF MODE
![Off Mode](https://user-images.githubusercontent.com/101312396/164612544-157131be-3b00-4218-804d-3e30c103b0a1.png)
* ON MODE
![On Mode ](https://user-images.githubusercontent.com/101312396/164612575-ef4453a7-5f5d-45a1-98f4-212815289286.png)



