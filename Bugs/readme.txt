BUGS by Bob Fairbairn

The Bugs program is meant to simulate the activities of a group of bugs living in a circular field. Four files are needed for the program to run: "bugs.htm", "field.gif", "green.gif", and "red.gif". All of the files must be in the same folder(directory).

1. OPERATING ENVIRONMENT
Bugs is written as a web page, with the file "bugs.htm" to be executed by a browser. It has been tested with Mozilla Firefox, Google Chrome and Internet Explorer and may or may not work with other browsers. Bugs relies heavily on Javascript, thus the browser must have Javascript enabled. The display resolution is best set to 1024 x 768 or higher.

2. CONTROLS
The titles in this section refer to the names of the controls as they appear on the screen.

2.1 Start or Restart
2.1.1 Reset
Clicking on this option initializes all the controls and clears the field.
2.1.2 10 Bugs
This option populates the field with 10 bugs. Each bug is represented by a letter, so that individual bugs can be recognized and followed.
2.1.3 25 bugs
This option populates the field with 25 bugs.

2.2 Motion
2.2.1 Off
When Motion is set "Off", the bugs do not move.
2.2.2 On
When Motion is set "On", the bugs move around the field. There is a good deal of randomness in their direction and speed of motion. The bugs will not crawl over each other; when two bugs meet, one of them will turn and go in a different direction. When a bug comes to the wall at the edge of the field, it will turn and go in a different direction.

2.3 Gather/Scatter/Flock
2.3.1 Off
When this control is set "Off", there is no effect.
2.3.2 Gather
When "Gather" is selected, the bugs come together into a group. This is accomplished by each bug individually recognizing the center of concentration of the other bugs and moving toward that center. The eventual location and shape of the group is not always easy to predict.
2.3.3 Scatter
When "Scatter" is selected, the bugs move as far from each other as possible. After a time of adjustment, they settle into a more or less stable arrangement.
2.3.4 Flock
When "Flock" is selected, the bugs tend to travel in loosely connected groups, as each bug moves ln approximately the same direction as its nearest neighbor. 

2.4 Mouse
2.4.1 Off
When "Off" is selected, there is no mouse effect.
2.4.2 Attract
To activate this option, select "Attract", then click the mouse anywhere within the field. A green dot will appear, and the bugs will move toward the dot until they are as close to it as they can get.
2.4.3 Repel
To activate this option, select "Repel", then click the mouse anywhere within the field. A red dot will appear, and the bugs will move as far away from the dot as they can get.
2.4.4 Find Food
To activate this option, select "Find Food", then click the mouse anywhere within the field. A green dot will appear, which represents "food" for the bugs. There are two ways for the bugs to find the food:
	a. A bug may randomly run into the food and "eat" some. When a bug has eaten, it becomes underlined.
	b. a bug which has eaten may meet another bug and will then tell the second bug that there is food, and where it is located. the bug which has been told about the food displays a gray background and begins moving toward the food. When it has eaten, its background turns off and it becomes underlined.
When the last bug has eaten, they all turn blue. This may take a while - be patient. If patience is a problem, temporarily selecting "Gather" can speed up communication between those who have eaten and those who haven't - but it can also cause a traffic jam around the food.

2.5 A Bad
When "A Bad" is selected, the "A" bug becomes repellant to the other bugs, and they move away from it. The "A" bug is unaware of the situation and continues its motion around the field. (Have you ever known anyone with chronic halitosis?)

2.6 Gather vs Mouse/A Bad
These options affect the interaction between simultaneous Gather/A Bad and Mouse activities.
2.6.1 Nearest
When "Nearest" is selected, each bug will be affected by whichever factor is nearest to it. For example, if "Gather" and "Mouse-Attract" are both active, each bug will be affected by either the group or the green dot, whichever is closest.
2.6.2 Undecided
When "Undecided" is selected, each bug will be randomly affected by either the group or the mouse dot. This causes a lot of "nervous" motion and a gradual migration of the group toward or away from the dot.