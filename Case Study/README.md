CASE STUDY
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

LOW LEVEL EMBEDDED SYSTEM
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

VENDING MACHINE
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Vending Machine](https://user-images.githubusercontent.com/98872937/154919230-d2f22938-d5be-4d52-86d1-3b5b3cbd9081.jpg) 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Explanation 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Power Supply Unit -
  The power supply unit consists of voltage, rectifier and voltage rectifier. 
  
  Volatge - From the main supply, 230V of AC Voltage is suuplied to the machine. 
   
  Rectifier - The rectifier converts the supplied voltage from AC voltage to DC voltage. 
  
  Volatge Rectifier - The converted voltage is then made to a constant of 5V. The 5V is then supplied to the microcontroller.

* Money Detection Box - 
  In case of proper money detection, then a signal will be sent to the internal circuit which consists of a Microcontroller. 
   
  The microcontroller operates the motors to dispense a a product the user has selected. 
  
  In case the money is not valid then it gets rejected. The money will be returned back to the user. 
  
  
* DAC - 

  The microcontroller gives the output in the form of digital data. This digital data has to be passed on to Relay drive. As Relay driver doesn't understand 
  the digital data, this digial data is converted from Digital to Analog. Then it is passed on to Relay Driver.

* Relay Driver - 
  A Relay driver is a circuit which can operate a relay so that it can function appropriately in a circuit.
  
  The Relay driver then can operate a Relay for switching operation in the circuit which can open or close, according to the needs of the circuit and it drives the motor. 
  
* Motor - 
  The Relay uses to drive using a Motor. 
  
  When the product required is selected by the user. The money is inserted and if accepted by the money detection box, a pulse is given to the Microcontroller. Thus the motor is   driven. 
  
  Motor inturn drives the spring attached to it. The spring rotates the product, which then slides out of the box. Thu the product selected by the user is deleviered by the       Vending Machine. 

  

![Smart Watch](https://user-images.githubusercontent.com/98872937/154919408-ee513ad8-cf62-488b-a2ed-cf049cafbee4.jpg)
