# Airsoft CS Bomb

This project is an open-source airsoft bomb simulator inspired by CSGO, utilizing Arduino and various components. It features multiple game modes like Counter Strike and Search and Destroy, each with two variations: Code and Hold. The bomb includes a customizable settings menu, allowing quick adjustments without reprogramming the Arduino. 

# Features
- CS Code/hold
- Search and destory Code/Hold
- Easy menu navagation
- Changeable settings on bored
- Lockable menu in match

Please note that I am not a professional programmer or designer. This project was born out of a passion for fun and a desire to support a local airsoft field with a new bomb simulator. The code and 3D models may not be optimized or perfect, but they "work" for their intended purpose. Feel free to tweak and adjust as needed to match your specific parts and requirements, as this project is about creativity and enjoyment.

## Table of content
[TOC]

# Gamemodes

### Counter Strike
CS Code is a gamemode like the video game counter strike where you have 2 teams one attacking team and one defending team where the goal for the attacking team is plant the bomb on a Bomb site/Location, where the defending team have to stop the attackers from planting the bomb or defuse the bomb if the attacking team have planted the bomb on the bomb site
##### Code
Code is a gamemode in which a random code is generated for the bomb. Players must input this code into the bomb to arm it. The bomb's code will be displayed in the top left corner, revealing one number at a time until the entire code is entered to either plant or defuse the bomb.
#### Hold
Hold is a gamemode wehre you have to hold a button on the keypad to start arm the bomb, it will show a prograss bar on the display of the bomb where it slowly ticks up to 100% armed and the bomb will go into defuse mode where the defending team will have to hold the botton to defuse it and stop the attacking team from winning, if you let go of the botton the prograss will slowly go down to 0% again

# Settings
#### Gamemodes
This setting allowes you can change what game mode you wanna play on the bomb
0 = <abbr title="Counter Strike">CS</abbr> Code
1 = <abbr title="Counter Strike">CS</abbr> Hold
2 = <abbr title="Search and destory">SAD</abbr> Code
3 = <abbr title="Search and destory">SAD</abbr> Hold
#### Time to Plant
This is the time the attacking team have to plant the bomb before the timer runs out and they will lose, 
This setting can be 1min to 60mins long
#### Time to Defuse
This is the time the defending team have to defuse the bomb before it blows up and the attacking team will win, 
This setting can be 1min to 60mins long
#### Code length
This setting changes the lenght of the code on the bomb 
This value ranges from 1 to 20 character long
#### Buzzer pitch
The buzzer pitch can go from 0 to 255 and it changes the pitch of the buzzer so the user of the bomb can pick a sound they like :P
This value ranges from 0 to 255
#### Mistake
This is a setting that gives the players a punishment if they type the wrong code in it can be turned off by changing it to 0
This value range from 0 to 60sec
#### Delay for numbers
This setting puts a delay on the numbers before they get displayed on the screen to make the arming and disarming of the bomb longer
This value ranges from 0 to 10sec
#### Auto check
Auto check is a setting that checks the code if its right or wrong along the way when you are trying to plant it or defuse it
This setting can be ON or OFF
#### Locked menu
Locked menu is a importen setting if you dont want players you go in the menu by acident or change values by mistake
If ON you wont be able to press the Knob to go back in the menu but you need to press * and # at the same time to unlock the bomb again
This value can be ON or OFF
#### Back light
Back light allowes you to turn on or off the back light of the LCD display
This value can be ON or OFF
#### Save as default
Save as default will save all of the setting on the bomb right now to its memory and load it in when the bomb is booted up and have it in the preset menu
#### Factory reset
Factory reset will turn all of the settings back to the default settings that it came with originally
# Presets
Presets is a menu for preset settings for gamemodes where its quick way of changing settings without going into setting and doing all manually
#### User Default
Uses the default setting that is used when booting up
#### GM/TTP/TTD/CL/DFN
This is the format i use to say the presets without typing everything out
GM = the Gamemode
TTP = Time to Plant
TTD = Time to Defuse
CL = Code lenght
DFN = Delay for numbers
