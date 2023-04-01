# HBNB

This is the console /command interpreter for the Holberton Airbnb clone project. The console can be used to store objects in and retrieve objects from a JSON.

### Supported classes:
* BaseModel
* User
* State
* City
* Amenity
* Place
* Review

### Commands:
* create - creates an object
* show - shows an object (based on id)
* destroy - destroys an object
* all - shows all objects, of one type or all types
* quit/EOF - quits the console
* help - sees descriptions of all commands

To start, navigate to the project folder and enter `./console.py` in the shell.

#### Create
`create <class name>`


#### Show
`show <class name> <object id>`


#### Destroy
`destroy <class name> <object id>`


#### All
`all` or `all <class name>`


#### Quit
`quit` or `EOF`

#### Help
`help` or `help <command>`

 the console also supports `<class name>.<command>(<parameters>)` syntax.


