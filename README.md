# Python-Hours-Minutes-to-Seconds-Converter
In this exercise, the challenge on Convert Hours and Minutes into Seconds
#A challenge on Convert Hours and Minutes into Seconds
#In this exercise, there is creating a function that takes two integers (hours, minutes), converts them to seconds, and adds them.
#The user needs to input the information using the keyboard, i.e., hours and minutes
#This exercise is based on the fact that 1 hour = 3600 seconds, and 1 minute = 60 seconds
hours = input("Hours   :  |  ")
minutes = input("Minutes :  |  ")
print("|--------------|")
secondsConversion = 3600*int(hours) + 60*int(minutes)
print("Conversion of " + hours + " Hours and " + minutes + " Minutes into Seconds is: " , secondsConversion)





**SAMPLE OUTPUT****
**
.....................................................
Hours   :  |  2
Minutes :  |  45
|--------------|
Conversion of 2 Hours and 45 Minutes into Seconds is:  9900
...........................................................
Hours   :  |  5
Minutes :  |  67
|--------------|
Conversion of 5 Hours and 67 Minutes into Seconds is:  22020
................................................................
Hours   :  |  4
Minutes :  |  34
|--------------|
Conversion of 4 Hours and 34 Minutes into Seconds is:  16440
--------------------------------
Hours   :  |  0
Minutes :  |  0
Conversion of 0 Hours and 0 Minutes into Seconds is:  0
Hours   :  |  0
Minutes :  |  59
|--------------|
Conversion of 0 Hours and 59 Minutes into Seconds is:  3540
