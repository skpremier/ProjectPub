%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Readme.txt file
%%
%% This file contains the manual for running JAR file for
%% reading CSV and Byte Format File and add to List Object
%% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

  To run this Jar requires you to have java 7 or 8 installed. (Typing "java -version" should return an answer like 1.8.) 

%%%%%%%%%%%%%%%%%
Program execution 
%%%%%%%%%%%%%%%%%
To invoke this program pass  with args
%%%%%%
Inputs Args
%%%%%%

Input File Name

        A name of a text file containing emplyee record.
       
Sort Type

        1 : Sort By FirstName
        2 : Sort By LastName
		3 : Sort By Date

        Default:Sort by Last Name
 
 java -classpath FileProcess.jar com.planet.FileProcess C:\\doc\\comma1.txt  3
 
        The command for executing the Java program is with command line arguments
		 
		 First  args Filename
		 Second args pass 1, 2 or 3   Sortby LastName =1 FirstName =2 Date =3

		java -classpath FileProcess.jar com.planet.FileProcess C:\\doc\\comma1.txt  3      
	
        
%%%%%%
Output
%%%%%%

        The outputfile is stored in working jar folder with filename output.txt

%%%%%%
JAVA CLASSES
%%%%%%
		
      Employee class to store Employess Obects
	FileProcess is Main Class file . Read the file in CSV or byte format
	Check if file contains comma then process as csv else byte format.
	
	  
	  


     

        

