# Lab 1: LED Animations

**School:** Ho Chi Minh City University of Technology  
**Name:** Huynh Tri Duc  
**Student ID:** 2452269  

---

**Project Overview**  
Source code and Proteus simulation for Lab 1, implementing custom LED animation sequences using GPIO control.

**Tools & Environment**  
* **Microcontroller:** STM32F103C6  
* **Development Environment:** STM32CubeIDE  
* **Simulation:** Proteus 8 Professiona  

**Animation Modes**  
* **Pattern 1-2:** State transitions for 2, 3 LEDs  
* **Pattern 3-5:** Traffic light with 7 segment LED  
* **Pattern 6-10:** Displaying clock using 12 LEDs  

**Pin Mapping**  
| Pattern | MCU Pin | Connected Device | Logic |
| :--- | :--- | :--- | :--- |
| **Patterns 1–2** | PA5 | LED_RED | Active Low |
| | PA6 | LED_YELLOW | Active Low |
| | PA7 | LED_GREEN | Active Low |
| **Patterns 3–5** | PA5 – PA7 | LED_RED_1, LED_YELLOW_1, LED_GREEN_1 | Active Low |
| | PA8 – PA10 | LED_RED_2, LED_YELLOW_2, LED_GREEN_2 | Active Low |
| | PB0 – PB6 | SEG_A – SEG_G | Active Low |
| **Patterns 6–10** | PA4 – PA15 | LED_1 – LED_12 | Active Low |

**How to Run the Simulation**  
1. Clone this repository to your local machine.  
2. Open `schematic/Ex<number>.pdsprj` in Proteus.  
3. Double-click the STM32F103C6 and choose to debug by using the respectively hex file  
4. Click Debug > Start VSM Debugging
