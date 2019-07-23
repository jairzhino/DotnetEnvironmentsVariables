# Environments Variables


# Presentation:

New projects has the specific connection database, logger level, etc. 
when its time to compile the Project to publish in Production Environment, it must be mandatory change the variables (database connections, logger level, etc). That’s can be dangerous if you forget to change one of the variables in the code.
 
For this cases  exist by default the files (appsettings.Development.json, appsettings.json) but if you want to add other Environment file its posible create it.
