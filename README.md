# Eye Tests on Demand

In this group project, our team designed and implemented an automated eye-testing system for patients to test their eyesight without needing a doctor’s instruction, either in a hospital or a public setting. My contribution was the development of the eye-testing algorithm. We collaborated with Addenbrooke’s Hospital in Cambridge.

The system consists of three main components: 
* TV 
  * displays symbols at a distance
* Phone/tablet
  * is in user's hands
  * gives instructions to the user
  * allows the user to select what letter/symbol they can see on the TV
* Server
  * manages communication between TV and phone

On setting up the TV in the given environment, the operator can make initial test configurations (setting the viewing distance, screen size, resolution, and test specific settings) to suit their requirements. Then, upon scanning a QR code displayed on the TV screen with their own device, the user is taken to a webpage that allows them to provide input to the eye-testing system. This page provides text instructions that guide the user through an eye-testing procedure, with letters being displayed to a medical standard on the TV screen. A staircase algorithm is run on the server, such that the user test will end after the letter size reaches a threshold and oscillates back and forth over that threshold a certain number of times to ensure that the outcome of the test is stable. At the end of the test, the user is informed via their own device whether or not it is recommended that they seek treatment. The user is also given an option to have the results emailed to themselves if they choose to provide their email address. If they decide to do this, a PDF is generated to be sent to the user, containing more accurate results represented in multiple different medically-recognized formats.

- Personal report [[PDF]](https://github.com/jancio/Eye-Tests-on-Demand/blob/master/Personal_report_GroupProject_JanOndras_2016.pdf)
