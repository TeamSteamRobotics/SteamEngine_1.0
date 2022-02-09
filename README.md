# SteamEngine_1.0
our scouting visualization and creation app to go alongside our android app

# how to use

the app consists of 2 main areas, the control bar and the window area

the control bar has all the controls in the order of, the frame your editing, wether or not you are editing, saving layout, team input, graph style, input order, and shown variable


if you want to move a frame select edit to true and drag your left mouse button to move and right to scale

press save layout to save your layout

each team input box is a team you can see on the graph, the first box shows on the table too

the box after teams is wether you want to see each round individualy or by games played

team input is where you enter the names and order of your input app, if you are using SteamTracker the code is {}, other wise put it in the order of team-rounds-vars-vars-etc

shown is what variable is being shown on the graph


the window area is where all your windows are the windows being, table, file sytem, graph, camera

table is a basic table to show the raw data from the first team

file system is where you chose to get and save your team json files

graph is where the graphed items show up, the numbers in the corner show your x (rounds or games) and y (value)

camera is wher you input your qr codes or data by hand, it has 4 main areas, the camera itself, data, calcs, and push button
  the camera itself is where you line up your qr codes to scan
  data is where the scanned values go, they must be in order of team input
  calcs is where you add any calculation vars, the top box is for the name, middle for numerator in var-var-var form, bottom is for the denominator (leave blank for it to use 1)
  push button pushes the data
  
