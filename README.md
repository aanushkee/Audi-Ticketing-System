# Audi Ticketing System

The aims and objectives are as follows:
● Online booking system for booking Audi tickets during Oasis
● Provision for the user to check event details including timings
● Provision for user to check seating availability
● Provision for admin to create new events/change details of existing events
● Provision for admin to track revenue for events and check seating availability

## Installation

Execution Instructions:
The code was tested on Pop!_OS 21.04 which is an ubuntu-based Linux distro using Visual
Studio Code. Instructions to execute the application are given below:

Install JDK 17 using sudo apt install openjdk-17-jdk

Download SDK from here.

Unzip it to a desired location

Add an environment variable pointing to the lib directory of the runtime in .bashrc

export PATH_TO_FX=path/to/javafx-sdk-17/lib

In VS Code settings.json file in the project directory, add the path to lib folder to
referencedLibraries like this:

```bash
{ "java.project.sourcePaths": ["src"], "java.project.outputPath":
"bin", "java.project.referencedLibraries": [ "lib/**/*.jar",
"/home/aviralomar/development/sdk/javafx-sdk-17.0.1/lib/*.jar" ] }
```

Install following: 
```bash
sudo apt install libswt-gtk-4-java
```

To compile the code go into the bin folder of the project directory and run: 
```bash
javac --module-path
```

```bash
$PATH_TO_FX --add-modules javafx.controls ../src/*.java -d .
```


To execute the application, from the bin directory, run: 
```bash
java --module-path $PATH_TO_FX
--add-modules javafx.controls Monopoly

```

## SOFTWARE REQUIREMENTS

Operating system: Windows 10 is used as the operating system due to efficiency
and user-friendliness

Programming language: Java is a high-level, class-based, object-oriented
programming language that is designed to have as few implementation
dependencies as possible. 

Java offers features like
1. Compiled and Interpreted.
2. Platform-Independent and Portable.
3. Object-Oriented.
4. Robust and Secure.
5. Distributed
6. Architecture-Neutral
7. Familiar and Simple.
8. Multithreaded and Interactive.
9. High Performance.
10. Dynamic and Extensible

## HARDWARE REQUIREMENTS

● Intel Core Processor
● 1 GB Ram

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

