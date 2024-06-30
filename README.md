# Threat-Modeling-Assignment
The student should show the ability to represent an application using data flow diagrams and identify/analyze the threats associated with various components in the diagram using a common threat assessment model.

Consider a sample web application that does the following:

Presents the user with a login page (username and password)
Uses an open source component to authenticate the user credentials against a database
If the username and password presented exist in the database, present the user with a message-of-the-day stored in the database
Allow the user to comment on the message-of-the-day (comments will be stored in the database)

Use ThreatDragon to create a threat model of the web application that was just architected:

Authenticate to ThreatDragon through your GitHub account
Select "Create a completely new, empty threat model"
Select the newly created repo
Use the main/master branch as prompted
Title should be "Initial Threat Model"
Owner, Reviewer, and Description fields are optional (using "test" for all values is fine)
Click to add a new diagram titled "Initial Threat Model Diagram"
Create a simple data flow diagram to model the web application, showing boundaries and flows between the user's web browser, the application, and the database
Use the sample threat model, main request data Flow, located in the topic Resources, as an example
Click on an element in the diagram and then click on Edit Threats
Add a new threat using the STRIDE model. Consider all threats open (not mitigated)
