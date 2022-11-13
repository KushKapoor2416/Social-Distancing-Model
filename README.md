# Social-Distancing-Model
This is a social Distancing Model that I created in Tinkercad , feel free to make changes.

![COA PROJECT KK-SK-2022](https://user-images.githubusercontent.com/91105941/201506531-b18917af-9f36-4520-b84d-11de98fb9f25.png)

ABSTRACT:
With its devastating spread, the continuing COVID-19 coronavirus pandemic has produced a worldwide calamity. Population vulnerability grows as a result of a lack of efficient restorative medications and a scarcity of vaccines against the virus. Because there are no antidotes available in the current circumstances, social separation is considered an acceptable precaution (norm) against the spread of the pandemic virus. By limiting physical contact between people, the danger of viral propagation can be reduced. The goal of this project is to notify someone if they are in close proximity to another person.
Furthermore, this could be loaded on mobile phones, and the individual might be warned if he or she came into touch with an infected person using the AAROGYA SETU app.

COMPONENTS USED:
TinkerCad circuit simulation software.



It is an online simulation software used for circuit design. It has all the electrical components required to build circuits and run them.

HARDWARE REQUIREMENTS: (On the tinkercad simulator)

●	Arduino UNO Board- is a microcontroller that is used to accept inputs from sensors connected and provide an output action on the desired device connected to it. The sensor inputs can be from light-detecting sensors, motion sensors (Ultrasonic or IR), temperature sensors, etc. The output from this device can be received through other output devices such as LED, Buzzer, Serial monitor, etc.
●	LM-35 Temperature Sensor- gives an analog output based on the instantaneous temperature value. This analog output is proportional to the instantaneous input.
 
●	Resistors- Resistors are passive devices that restrict the flow of current or divide the voltage through the circuit. The input power passes through these resistors and then to the sensors to avoid damage.

●	Breadboard- is the basic component of any circuit building process. All components, be it input sensors or output display devices are connected to the power supply, microcontroller using wired connections through a breadboard. The holes in the breadboard are in series. There are various sizes like full-sized, half-sized, and mini breadboards.

●	Piezo Buzzer- It is an electrical component that generates a beep sound on receiving an input. It works on the principle of piezo crystal.

●	Jumper Wires-These are the main components that are used to establish the connections between different devices of the circuit.



WORKING:

The Arduino UNO R3 is used in this project. This is accomplished through the use of SONAR, which determines the distance between the object and the source. As a result, Arduino uses the logic from the Arduino's code to light up more lights in the NeoPixel ring.

The Arduino's D3 terminal provides input to the NeoPixel Ring, while the other two terminals are linked to the power (5V) and ground connections. The SONAR Trigger and Echo Terminals are linked to D5 and D6, respectively, with Arduino providing power and grounding.

The piezo (buzzer) is linked to the D2 pin, while the buzzer's other end is connected to the ground (Power Section of Arduino).

EXPECTED RESULT:

The object's distance from the source varies, and NeoPixel light produces different outputs in different areas.

The NeoPixel Ring displays the intensity of proximity to another person, and if the distance is less than 1 meter, the buzzer sounds a warning. 

ADVANTAGES:
1)	It helps in maintaining social distance to prevent spread of disease .
2)	It prevents spread of diseases like Covid-19 .

