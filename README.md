# Rofida Chatbot
This repository is about a chatbot.
<p><img src="./chatbot.png" width="400" height="600" title="chatbot"></p>

 ## Description 
<p>This project is a chatbot called Rofida who works as an assistant.</p>
<p>There are four pages in this repository and two databases</p>

#### 1. robotConntrolPanel.html:
 
This page includes the code for HTML, there are 3 sections in the code 1- to control the arm, 2- is to control the base of the robot and 3- is to add chatbot to the website page.

* The robot arm section:

There are 6 servos to control the arm of the robot that's why there are 6 range sliders, each slider has values that range between 0 and 180, also there are two buttons one for saving the values from the range sliders to the database at MySQL and the other is to display the values in separate page.

<div><img src="./robotArmCode.png" width="450" height="350" title="robotarmcode">
<img src="./buttons.png" width="450" height="350" title="buttons"></div>


* The robot base section:

There are 5 buttons each button moves the base in a specific direction and the direction is saved to the database.

<img src="./robotbasecode.png" width="450" height="300" title="robotbasecode">

* chatbot section:

<img src="./chatbotcode.png" width="450" height="300" title="chatbotcode">

#### 2. robotControlPanelStyle.css:

This page include the design of the elements on the html page like the background, fonts and the layout style.
<p><img src="./robotstylecode.png" width="450" height="300" title="stylepage"></p>

#### 3. robotdb.php:

This page connects the values of the servos and the directions of the base to the databases.
<p><img src="./robotdbcode.png" width="450" height="300" title="robotdbcode"></p>

#### 4. skill-تحدث.json

This is the json file that contains the property of the chatbot
<p><img src="./jsonFile.png" width="450" height="200" title="jsonFile"></p>

#### 5. robotcontroller.sql:

This is the robot arm database file.
<p><img src="./database.png" width="450" height="200" title="armdatabase"></p>

#### 6. robotbase.sql:

This is the robot base database file.
<p><img src="./basedatabase.png" width="450" height="200" title="basedatabase"></p>
