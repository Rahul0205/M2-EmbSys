# Testplan and Output

Test plan is created and verified on both manual and automated manner

## HIGH LEVEL TEST PLAN / Integrated test plan

|SL no|                                         description  |Exp i/p        |Exp o/p          |Actual o/p       |Test Type|
|-----|------------------------------------------------------|---------------|-----------------|-----------------|---------|
|1    |To check if the servo motor is rotating btw(0 to 180) |Message passed |angling of motor |angling of motor |technical based|
|2    |To check if message is displayed of object distance   |sensor detects |message displayed|message displayed|technical based|
|3    |Ultrasonic sensor should detect the object            |Object in range|Detected         |Detected         |
|4    |Servo motor should pause when Ultrasonic sensor detect|Object in range|Servo motor stops|Servo motor stops|