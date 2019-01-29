In order to change the color table of the robot we must do the following:

1) Connect to the robot via ethernet or wifi. If we are unable to connect please follow the steps in the tutorial ConnectToTheOldSoccerPlayerV3_3 
{https://github.com/AnonKour/LabTutorials/tree/master/HowToS/ConnectToTheOldSoccerPlayerV3_3}
2) While in terminal navigate to the directory /naoqi/config.
3) Open the vision.xml with an editor, for example:
```
nano vision.xml
```
- In case of an error {example: Error opening terminal:xterm-256color} use a different terminal.

4) In this xml file we see under the <!-- Configuration files for Segmentation --> the different options for the top and bottom segmentation
- We can choose between the 1-lab**-1667.conf for the lab or 1-amplitheatro-.conf for the amphitheater by manipulating the commenting of the file.
- These file can be found at the /naoqi/config/colortables
5) We save the file and restart Naoqi by typing in therminal:
```
nao stop
nao start
```
or 
```
nao restart
```
although the second option doesn't seem to work all the time.
