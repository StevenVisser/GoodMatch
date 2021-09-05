# GoodMatch
Read Me file for the Derivco Developer Graduate Assessment.

Author: Steven Visser
Date: 04/09/2021 [14:43]

For this assessment, I have completed all compulsory and optional tasks.


Before you run the Good Match program, open the terminal in the directory where goodMatch.js is.
Input the following:

	npm install
		
and press enter.

This will install the node modules defined in the package.json that are required for the Good Match program to run.

To run the program, in the same terminal, input the following:

	node goodMatch.js csvName.csv

and press enter.

goodMatch.js : name of the program file.

csvName.csv  : command line parameter that takes the name of the csv file that you wish to use in 
	       the program.

The program that I have written will defend against incorrect file types and files that do not exist.
It will output the error to the console to inform the user of the issue.
If the csv file is not in the same directory as the program file, please ensure that you use the whole 
file path.

The program will output the results to the output.txt file at the end of every run. The output has been
formatted as follows:
	
	The results of Males matched against Females
	The results of Females matched against Males (the data set reversed)
	The combination results of the above. This section averages the above scores.
		
Each output section will be ranked in descending order.

The program will also continuously write logs to the logs.txt file. This file keeps track of program 
execution time and errors that were encountered with input over each run.

All files that pertain to the final optional task can be found in the FrontEnd(Optional) folder.
To run this task, open the goodMatchFrontEnd.html with your browser.

The browser will prompt the user for 2 names. Once the names have been entered, the Match button should
be clicked. This will send the names to the Good Match Algorithm and return a compatibility score.

I only designed the front end to be used locally for this task.
