%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Similarity Tool V_1

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

DESCRIPTION

This package, once the set of entities in Input has been chosen,
is used to do two things at the same time:

i)Find characterizations.

ii)Find the essential expansion of the set of entities given in input.

The following points will explain how to best use the package.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

DISCLAIMERS

1) Unless otherwise specified:
-Please do not modify the contents of the files. 
-Please do not modify the names and the locations of the files.

2) Currently this tool only works on Windows.

3) Always give at least two entities as input.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

USAGE

Please follow the steps below.

1) Choose which set of data to use. 
The following tool provides two sets of data to choose from. 
The first is the transcription of the graph in the presented article.
You will find it in "Similarity-Prototype\Dataset\PaperExample".
The 2nd database was manually created using data on top-performing films.  
According to Google they are among the most relevant of the last 30 years.
You will find it in "Similarity-Prototype\Dataset\Films".

2) Copy both "00_relational_facts_kb.txt" and "03_gamma.txt".
Past them into "Similarity-Prototype\Input".
Doing so you will overwrite the files previously contained in it.

3) Choose the entities for which you want to find the characterization.
Report them, one per line, in "Similarity-Prototype\Input\05_unit.txt".
The file contains example lines that can be replaced.
The entities of interest must be chosen starting from "List_of_Entities.txt".
Please note that the two dataset comes with distinct "List_of_Entities.txt".

4) Right-click an empty spot in the root folder while pressing SHIFT.
Select Open PowerShell Window/Terminal Here or Open Command Prompt Here.
Issue the command "java -jar Characterizations.jar" and press Enter.

5) Results will be in "Similarity-Prototype\Output".

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

EXAMPLES

In "Similarity-Prototype\Examples" you will find some characterizations. 
The file name represents the initial input.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

SUGGESTIONS AND COMMENTS

If you use the film dataset it is recommended to give two entities as input.
This first version is not optimized with respect to execution times.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%