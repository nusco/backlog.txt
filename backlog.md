#backlog.txt

This is the backlog for the _backlog.txt_ project. We eat our own dog food.


##Proof of Concept

This is the minimal stuff we need to check that the idea actually works and to ask for preliminary feedback from a few friends.

xxx Mimimal version of the `backlog` tool  

    Just dumps Features and Stories to the console, in color  

xxx Put Python package on PyPy as version 0.0.1  

    Taz will take care of this  

xxx Put version 0.1 of the specs on the wiki  

    Discuss these with Taz  


##MVP

This should make the project worth a try for the general public. Then we ask for feedback from a larger group, like one of our mailing lists.

xxx The console dump includes Comments  
xxx The console dump includes Properties  
xx The console dump includes Markdown formatting  

    Maybe only for some elements, depending on which Markdown library we can find.  

xxx `backlog -h` prints usage help  
xxx Explicit error message (with help and link) if no backlog file is found  
xxx `backlog init` creates an empty backlog  
xxx `backlog html` exports nicely formatted HTML  
xxx `backlog open --html` attempts to open the HTML backlog in the browser  



##Friendly Tool
xx  `backlog init` asks for confirmation to overwrite existing backlog  
xx  Simply use `backlog` as a shortctut to `backlog print`  
xx  Use `bl` as a shortctut to `backlog`  


##Scripting

This should make the project good enough to go public.

xxx Make the command-line toolset accessible as a Python library  
xxx Publish scripting example on Wiki  

    For example, show how to calculate the total story points in the backlog  


##Advanced Printing

xx  `backlog print --top` prints the top Feature  
xx  `backlog top` prints the top Feature  
x  `backlog 10` prints the first 10 Features  
xx  `backlog --features` prints the Features without User Stories and comments  
x  The help text explains User Story colors  


##Export Formats

xxx  `backlog csv` exports to a CSV file  
xx  HTML export includes CSS for collapsible sections  
xx  `backlog excel` exports to an Excel file  
xx  `backlog open --<format>` attempts to open the format in the associated application  


##Property Filters

Is this actually useful, or overdesign? Decide later.

xx  `backlogfilter <name>:<value>` shows the User Stories with the specified property  
xx  `backlogfilter mandatory` only shows the Mandatory stuff  


##Syntax Files

xxx  Syntax file for vim  
xxx  Syntax file for one popular text editor  
xx  Syntax files for other text editors  

    Decide which ones  


##Multiple Backlogs

xxx  `backlog` accepts the name of the backlog file as an additional parameter  

