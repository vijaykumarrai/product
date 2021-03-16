Application Name :	ZIPRanges

This application takes set of zip code range and returns minimal list of restricted ranges.

Input : Array of zip code values in the format E.g.:- [94133,94133] [94200,94299] [94600,94699]

Steps to Install and Run :

Attached zip file is a maven project.

You can build the application using the command
	mvn clean install package

Run :
	com.zip.range.generator.Tool
	is the Entrypoint of the application which contains main method. You can run the class through command line and provide the input as scanner input.

Run test cases :
	You can run the Junit test cases using the following command.
	mvn test



