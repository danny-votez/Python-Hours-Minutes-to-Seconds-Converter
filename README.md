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
