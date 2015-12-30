# cpp-hello-world
C++ Hello World Tutorial for Mac OSX

# Getting Started
* Install XCode - [https://developer.apple.com/xcode/](https://developer.apple.com/xcode/)
* Create a 'Workspace' 
  * Start XCode
  * File -> New -> Workspace -> choose a folder for your workspace
  * Call it ``demos``


#Create a 'Project'
* File -> New -> Project -> choose OSX -> Application -> Command Line Tool
* Product Name: ``cpp-hello-world``
* Organization Name:  ``stujo``
* Organization Identifier: ``com.stujo.demos``
* Language: ``C++``
* Next
* Create a new empty folder ``hello-world`` and select it
* Check Create Git Repository (optional)
* Add to ``demos`` workspace (optional)

This creates the following ``main.cpp`` file:

```
  #include <iostream>
  
  int main(int argc, const char * argv[]) {
      // insert code here...
      std::cout << "Hello, World!\n";
      return 0;
  }
```

# Building the Project

* Build and Run using ``Cmd-R``
* Watch the Output window at the bottom right 

