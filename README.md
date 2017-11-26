# ItemCatalog

This repository contains the files required to deploy and run the Item Catalog done as part of the 
Udacity FSND.  


## Project files
   1. The project solution mainly has the itemcatalog.py, catalogdb.py, database_setup.py 
      and various html templates named according to the handling they do.

   2. pylint has been run and comments addressed except for adding comments 
      where its simple and self explanatory

   3. some of the functions used were done as part of excercises 
      in earlier courses and have been reused in the project.
   
   4. Minimum styling has been done as it is not the focus of this project. 

## How to open/run the project
   1. Install Vagrant and VirtualBox found [here](https://github.com/udacity/fullstack-nanodegree-vm)   
    
   2.  Clone the fullstack-nanodegree-vm
    
   3.  Launch the Vagrant VM (vagrant up)Setup.
    
   4.  Download the ItemCatalog and navigate to folder.
    
   5.  In terminal windown, run cmd "python logofcategories.py" to create and populate the ItemCatalog.db 
    
   6.  run cmd "python itemcatalog.py" to start the webserver for itemcatalog
    
   7.  The setup is done to run webserver on localhost:5000.  Open Google Chrome and navigate to localhost:5000
