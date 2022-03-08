# Testplan and Output

Test plan is created and verified on both manual and automated manner

## HIGH LEVEL TEST PLAN / Integrated test plan

|SL no|                                         description  |Exp i/p        |Exp o/p          |Actual o/p       |Test Type|
|-----|------------------------------------------------------|---------------|-----------------|-----------------|---------|
|1    |To check if the servo motor is rotating btw(0 to 180) |Message passed |angling of motor |angling of motor |technical based|
|2    |To check if message is displayed of object distance   |sensor detects |message displayed|message displayed|technical based|
|3    |Ultrasonic sensor should detect the object            |Object in range|Detected         |Detected         |technical based|
|4    |Servo motor should pause when Ultrasonic sensor detect|Object in range|Servo motor stops|Servo motor stops|technical based|


## LOW LEVEL TEST PLAN / Unit test plan


|SL no|                                         description        |Exp i/p        |Exp o/p          |Actual o/p       |Test Type|
|-----|------------------------------------------------------------|---------------|-----------------|-----------------|---------|
|1    |When power supply is given all the components should activate|Power input|Components Activated|Components Activated|technical based|
|2    |To check if Servo motor is working    |Message passed in code |angling of motor|angling of motor|technical based|
|3    |To check the message displayed |Message passed in code|message displayed|message displayed|technical based|
|4    |Servo motor should pause when Ultrasonic sensor detect|Object in range|Servo motor stops|Servo motor stops|technical based|