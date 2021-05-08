# Iot-Based-pandent-and-gloves
## Voice command to make alarmimng sound
We have registered few voices and commands which  women will speak when she will get in danger during night time or in any other situation. Then alarmimng sound will buzz and it will alert nearby people that something is happenning. 
Women can control the Iot pendant through their voice. You can register general voice commands, which trigger a listener when the user speaks them. The voice control service recognizes the sound data recorded by the user and sends the result as a predefined command.

The Voice Control API is mandatory for Wearable devices.
The main features of the Voice Control API include:

Managing commands

You can use the voice control service to register commands as foreground type. When the user speaks a registered command, the listener returns the recognition result.

Retrieving information

You can get the current language. A command is valid only when the command language is the same as the current language. The current language can be changed with the voice control setting application or by changing the display language on the device.

You can get a notification of the language change in a listener. If the display language is changed to a non-supported one, the voice control language changes to English.
