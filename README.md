Introduction
This will be the documentation laying out the project plan of the “Pathway Algorithm WebApp” by Jacob Hoard.
The intention for this document is the layout the development process of “Pathway Algorithm WebApp” by giving the current and future developers a plan of action. The document will include a summary of functionality, platform requirements, risk management and scheduling and delivery estimation. 
Overview
The functionality and purpose of this project is to allow users to see a visualization of the A*, D* and Dijkstra Algorithm. The web application will allow users to select a starting and end point inside of a set grid. After the start/end nodes have been selected the user can now set-up a roadblock inside the grid without fully encapsulating the end point. This will allow the user to see how the algorithm moves through the maze they have created. This will give them a better understanding of how the selected algorithm functions in the environment they created. 
Customers
The idea behind this application is to make a visualization for users to compare how each algorithm works in an environment created by them. This will hopefully give them a better understanding of how the path is chosen or at least the process in which the algorithm selects the path to find the final node. 
Functionality
•	Drop down with the choice between 3 algorithms
•	Ability for users to create roadblocks for the algorithms to work around
•	Ability for users to select a start/end node 
•	Visualization of the pathing the selected algorithm takes 
•	The ability to see the performance of each algorithm i.e., how long it took to work the maze
•	The user can slow down the algorithm which would give a better visualization since it would not complete instantly
Platform
Webapp possibly hosted on Heroku many unknowns in this environment. I do not know if it is possible to use NodeJS as a backend on the hosting server. 
Deliverables
•	Project Initiation and Planning
•	System, Interface, and Data Design
•	System Development
•	System Testing
•	Deployment
•	Implementation Review

Scheduling and Estimates

Milestone	Description	Release Date	Version
M1	Front end design for the Interface	Feb 21st	V1
M2	Back-end connected to database service	March 21st	V1
M3	Create the views to mesh front and back end	April 1st	V1
M4	Integration Testing	April 1st-30th	V1
M5	Testing for Release	April 1st-30th	V1
M6	Final Release	May 4th	V1

Technical Process
The following languages will be used to develop the application:
Front-end development: React, JavaScript, HTML/CSS, C# (this needs to be decided upon)
Back-end development: MySQL, NoSQL, Postgres, Node.JS (this also needs to be discussed what would be best)
