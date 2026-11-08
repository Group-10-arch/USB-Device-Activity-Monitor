USB Device Activity Monitor
**SDN260S Software Design II – Group 10 Project**

## 1. Project Description
The USB Device Activity Monitor is a Java application developed to monitor USB device connections and disconnections. It records device activity and allows users to view and manage event logs.

## 2. Project Objectives
- Monitor USB device activity.
- Detect device connections and disconnections.
- Record events with timestamps.
- Store event logs for future reference.
- Provide users with an interface to view and search activity.

## 3. Main Features
- Background USB device monitoring.
- USB device information and metadata extraction.
- Event logging with timestamps.
- Search and filter functionality.
- GUI and CLI interfaces.
- CSV log export.
- Error handling and diagnostic features.

## 4. Technologies Used
- Java
- NetBeans IDE
- Maven
- Java Swing
- Object-Oriented Programming
- File Handling
- Multithreading
- Collections and Regular Expressions

## 5. System Design
The application uses a modular object-oriented design. Its main components include:
- **USBMonitor:** Monitors USB device activity.
- **USBDevice:** Represents USB device information.
- **EventLogger:** Records and manages event logs.
- **ApplicationController:** Coordinates application operations.
- **GuiApp:** Provides the graphical user interface.
- **CliApp:** Provides the command-line interface.

## 6. Testing
The application was tested using different USB devices, including flash drives, external storage devices, mice and keyboards. Testing also considered rapid connection and disconnection events, unreadable device information and log-handling errors.

## 7. How to Open the Project
1. Download or clone this repository.
2. Open the project using NetBeans IDE.
3. Allow Maven to load the project dependencies.
4. Locate the application's main class.
5. Run the application.

## 8. Project Group
**Group 10 – CPUT SDN260S Software Design II**

This project demonstrates the application of software design principles, object-oriented programming, multithreading, data structures and file handling.
