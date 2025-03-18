# a07g-exploring-the-CLI

* Team Number: 02
* Team Name: APATHY Rover
* Team Members: Maryam Ali, Chris Connolly
* GitHub Repository URL: https://github.com/ese5160/final-project-a07g-a14g-t02-a-p-a-t-h-y
* Description of test hardware: (development boards, sensors, actuators, laptop + OS, etc)

## 0. Install Percepio

## 1. Software Architecture

1. **Updated SRS and HRS**

2. **Task Block Diagram**

3. **Task State Machines**

## 2. Understanding the Starter Code

1. What does “InitializeSerialConsole()” do? In said function, what is “cbufRx” and “cbufTx”? What type of data structure is it?

2. How are “cbufRx” and “cbufTx” initialized? Where is the library that defines them (please list the *C file they come from).

3. Where are the character arrays where the RX and TX characters are being stored at the end? Please mention their name and size. Tip: Please note cBufRx and cBufTx are structures.

4. Where are the interrupts for UART character received and UART character sent defined? 

5. What are the callback functions that are called when:

- A character is received? (RX) 

- A character has been sent? (TX) 

6. Explain what is being done on each of these two callbacks and how they relate to the cbufRx and cbufTx buffers. 

7. Draw a diagram that explains the program flow for UART receive – starting with the user typing a character and ending with how that characters ends up in the circular buffer “cbufRx”. Please make reference to specific functions in the starter code. 

8. Draw a diagram that explains the program flow for the UART transmission – starting from a string added by the program to the circular buffer “cbufTx” and ending on characters being shown on the screen of a PC (On Teraterm, for example). Please make reference to specific functions in the starter code. 

9. What is done on the function “startStasks()” in main.c? How many threads are started?

## 3. Debug Logger Module

## 4. Wiretap the convo!

1. What nets must you attach the logic analyzer to? (Check how the firmware sets up the UART in SerialConsole.c!)

2. Where on the circuit board can you attach / solder to?

3. What are critical settings for the logic analyzer?

### Hardware connections

### Decoded message

## 5. Complete the CLI

## 6. Add CLI commands

### Video Link

## 7. Using Percepio

### Percepio Trace