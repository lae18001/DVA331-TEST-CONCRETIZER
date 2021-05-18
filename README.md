# DVA331-MERGER
## Description
The main task of the script is to merge together two files with the relevant parts taken from both of them and create the new file, 
hence the name of the script - Merger.
The implementation of the script is a process of the  new test case creation while reading the rows from a csv-file.
Input  values  for  those test cases are set during the iteration process over each created data element’s variable tags. 
The  script uses library  called xml.etree.ElementTree that is made especially for parsing, creating and modifying xml files. 

## Script Execution
For the merging process to begin, the user first needs to specify the names of the files used in script (See the picture below). 

![TheScript](https://user-images.githubusercontent.com/48024044/118607496-f0fe5f80-b7b8-11eb-9dbd-7e133757bce3.JPG)



- The csv-file, holding all the input values 
- The PLCopen XML file that will be parsed and used as a template for the new test case creation.  
- The output PLCopen XML file, that will be created holding all the newly generated test cases.

In order to execute the script, all the previously mentioned input files and the script itself needs to be located in the same file folder on the users computer.  
Then the user needs to open the Command Prompt and specify the path to this folder and run the script or simply open the Windows  Power  Shell  from  the  folder  and  run the python script using *python* command.

## The Outcome
If the execution of the script went as expected, the number of created test cases will be printed out on the screen as well as the message of successfully created .xml file.
 
