# Core-Data
Learning Core Data (Swift iOS)


### What is Core Data
> Core Data is the combination of Object graph Mapper and a Persistant Framework. 
  1. Object Graph: Making relationship bettween objects (Model) . Like Books and Author. Core Data first jobe is to make the relationship .
  2. Persistant Framework: To save delete update data.
  
  
### Managed Object Model: 
> NSManagedObject to creat model Like Book info. Desining the Managed Object Model is the first part to start using Core Data Stack

### Manage Object Context: 
> Plays central role in managing the object in graph. Context keeps track of all changes in the object graph and when we want to save then its hands over to persistant container. All Managed Object must be resistered with a context. Gives undo and redo options. Its uses Command Pattern. NSManagedObjectContext Class. 

### Persistant Store Coordinator: 
> Its plays the main role of saving data. 
