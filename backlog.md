#Backlog.txt

This is the backlog for the _backlog.txt_ project. We eat our own dog food.


##Proof of Concept

This is the minimal stuff we need to check that the idea actually works.

xxx Basic version of the `bl` tool (just dumps the backlog to the console, in color)  
xx  `bl -h` prints command-line help  
xxx Release Python package  

    * assigned to: Taz  
xxx Version 0.1 of the specs  


##Print Backlog

xx  `bl print --top` prints the top Feature  
xx  Simply type `bl` as a shortctut to `bl print`  
xx  `bl top` prints the top Feature  
x  `bl 10` prints the first 10 Features  
xx  `bl --features` prints the Features without User Stories and comments  
x  The help text explains User Story colors  


##Export Formats

xxx  `bl csv` exports to a CSV file  
xx  `bl excel` exports to an Excel file  
xx  `bl html` exports nicely formatted HTML  
xx  `bl open --<format>` attempts to open the format in the associated application  


##Property Filters

Is this actually useful, or overdesign? Decide later.

xx  `bl filter <name>:<value>` shows the User Stories with the specified property  
xx  `bl filter mandatory` only shows the Mandatory stuff  


