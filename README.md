# CodeGuideLines for iOS (Swift/Objective-C)
***
## Project structure
* All source files **should** located in Classes, external libraries should be linked though Cocoapods/Carthage.
### Folders semantic
* *Extentions* - contain extetion to existing classes for example  **UIColor+Hex.swith**
* *Models* - contain data classes, sample CoreData entities or Realm entities.
  * *Constants* - constants :), notification names, project settings, third party libraries keys
  * *Entities* - 
![alt Project stucture sample](https://raw.githubusercontent.com/ihsuropu/CodeGuideLines/Develop/Assets/ProjectStucture.png)

* Header & Footer only XIB (Do not use storyboard)
* Never pass Mutable objects as parameters
* Method should invoke as method not as property
* Sort all classes alphabeticaly !!!
* Minimum usage self variable in class functions (pass all nessesary data as parameters).
