# Push-button-counter
#Company name- CODTECH IT solution
#Name - Pradeep khandu Ajetrao 
#INTER ID - CT08KSD
#Domain - Embedded system 
#Duration - 4 weeks 
#Mentor - Neela Santosh Kumar
#Description -  
This project is a Push Button Counter simulated in Tinkercad, designed to increment a numerical value each time a button is pressed. The system is built using an Arduino Uno, a 7-segment display, a push button, and two resistors.

Working:-
1. The push button is connected to a digital input pin of the Arduino Uno and configured with an internal pull-up resistor.
2. The 7-segment display is wired to the Arduino, with individual pins controlling the segments.
3. When the button is pressed, the Arduino detects the change in state and increments a counter variable.
4. The counter value (0-9) is displayed on the 7-segment display using a function that maps the numbers to the appropriate segment activation.
5. The system includes debouncing logic to prevent unintended multiple increments due to mechanical bouncing of the push button.
6. Once the count reaches 9, it resets back to 0 and continues counting.
This project demonstrates digital input handling, debounce techniques, and 7-segment display control, making it an excellent introduction to embedded systems and microcontroller-based counting applications.

