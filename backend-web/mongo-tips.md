
# Mongo tips and tricks 

How to import a json file or csv file into mongo.

change into the directory where the file you want to import is located, then type 
``` mongoimport --db <db-name> --collection <coll-name> --type json --file <file-name> --jsonArray
``` into the terminal 

if you want to import a csv file change ```--type json to csv```

