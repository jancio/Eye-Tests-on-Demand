# Eye Tests on Demand

System for automated eye-testing that can be used in a public setting or in a hospital. 

The system consists of three main components: 
* TV 
  * displays symbols at a distance
* phone 
  * is in user's hands
  * gives instructions to the user
  * allows the user to select what they see on the TV
* server
  * manages communication between TV and phone

On setting up the TV in the given environment the operator can make initial test configurations (such as viewing distance, screen size and resolution, and test specific settings) to suit their requirements. Then, upon scanning a QR code displayed on a TV screen with their own device, the user is taken to a webpage that allows them to provide input to the eye-testing system. This page provides text instructions that guide the user through an eye-testing procedure, with letters being displayed to a medical standard on the TV screen. A staircase algorithm is run on the server, such that the user test will end after the letter size reaches a threshold, and oscillates back and forth over that threshold a certain number of times, to ensure that the outcome of the test is stable. At the end of the test, the user is informed via their own device whether or not it is recommended that they seek treatment. The user is also given the option to have the results emailed to themselves if they choose to provide their email address. If they choose to do this, a PDF is generated to be sent to the user, containing more accurate results represented in multiple different medically-recognised formats. 
