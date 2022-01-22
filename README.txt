CELSUS STREAM TOOL USEAGE GUIDE
*******************************
VERSION B.1.0.0
*******************************

1) Install .Net 6.0 DESKTOP RUNTIME ||||| APP WILL NOT RUN WITHOUT THIS |||| https://dotnet.microsoft.com/en-us/download/dotnet/6.0
2) Run the CST.EXT file
	i) You will get a popup asking to allow a node.js sever to run
	ii) this is used to send data to the web page and is required.
3) In the 'HTML Files/Mockup' folder open the 'StreamInGameMockUphtml.html' file
4) Change any of the player info
5) Tell me if something breaks (@celsus#7982 on discord)

HOW TO USE SMASH GG
1) This app allows users to gets sets from a smash.gg tournamnet
2) To do this click on the "Stream Sets" button
3) Click on the "Set Tournamnet Slug" Button
4) Paste in part of the link to the tournamnet and click the update button
	i) its the "/tournament/[Tournamnet Name]"
	ii) pasting anything other than that part of the link will PROPBABLY crash the program
5) Click on the "Set Smash.gg Auth Token" Button
6) Pase you Smash.gg auth code in and press update
	i) You can create an auth code by going to your smash.gg account and going into the developer
	settings
	ii) Save this key locally as well.
7) Click the "Update" Button
8) Select a set

*******************************
KNOWN ISSUES

-No exception proofing, expect crashes when using the smash.gg stream queue page

*******************************
CHANGE LOG

- HTML no longer looks as bad :)
- Added Smash.gg integration
- Included BiB3 in game overlay



