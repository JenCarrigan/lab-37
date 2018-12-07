![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Project Name

### Author: Student/Group Name

### Links and Resources
* [Lab-Context Sandbox](https://codesandbox.io/s/7k8o5pw246)
* [Lab Sandbox](https://codesandbox.io/s/oly3o4263q)

### Lab-Context Modules
#### `index.js`
Renders Main function which call App class

#### `app.js`
App class renders GenericContext Class, which wraps around Content class, which wraps around Jen class

#### `context.js`
Function GenericContext creates React context
SettingsProvider class sets state in constructor
 Methods
  changeTitleTo: sets state for title property
  Rendersprops children wrapping it in context container

#### `content.js`
Consumes GenericContext and returns title

#### `jen.js`
Consumes GenericContext and returns button to change title.

### Lab Modules
#### `index.js`
Renders and provides store to App

#### `app.js`
Renders LoginContext, Login, and the Auth middleware

#### `context.js`
Provides context to its children

#### `login.js`
Renders the login page and get status of login

#### `auth.js`
Checks the capabilities of the user to render certain components/elements

#### `list.js`
Wrapped Add New button in Auth create
Wrapped Edit button in Auth update
Wrapped Delete button in Auth delete

#### `record.js`
Wrapped entire form component in Auth create

#### UML
![Lab-Context](https://raw.githubusercontent.com/JenCarrigan/data-structures-and-algorithms/master/%3Aassets/lab-context-UML.jpg)
![Lab-37](https://raw.githubusercontent.com/JenCarrigan/data-structures-and-algorithms/master/%3Aassets/lab-37-UML.jpg)
