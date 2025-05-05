# CyBot-IRoomba-Code
This repo holds the Python GUI and embedded C code for the CyBot IRoomba Group Final Project. <br/>
# Python GUI
  - Communicates over a WebSocket with the CyBot, which is used to send and receive commands.
  - Displays a polar plot of sonar sensor data mounted on the 180-degree servo.
  - Displays angle, sonar, and IR in a table.
  - Displays cliff and bump sensor status.
  - Includes a punching Cy logo. <br/>
# Embedded C code
  - Uses a mix of open interface and manually programmed peripherals.
  - Contains a manual mode operated from the Python GUI and an automated mode.
  - Uses fundamental embedded C code practices: Bit ops, modular design, descriptive declarations, and memory conservation.<br/>
# Objective
The project objective that was chosen was a mock bomb defusal. The Roomba controlled by the user would navigate the test field using the Python GUI. Once the "town square" (black box) was found, the onboard computer would take control and find the largest pillar (bomb) and drive towards it, effectively disarming the bomb. <br/>

**The Python GUI was created with the help of online sources, university databases, and OpenAI to help with debugging. It was also created with no prior Python GUI experience and minimal Python knowledge in the span of 2 weeks. It was a valuable learning experience.**
