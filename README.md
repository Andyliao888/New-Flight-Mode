# New-Flight-Mode
Note: I use the Qtcreator in ubuntu16.04

1 I add a new flight mode named ACQIN in line40 in mode.h and define its class called ModeACQIN and its definition is similar with ModeStabilize.

2 After I finished the step 1,I create a new .cpp file named mode_acqin.

3 I add the the flight mode which is located at line902 to Copter.h and define the variable called MODE_ACQIN_ENABLED in config.h

4 Finally, I add the flight mode into mode.cpp and it is located at line 52
