
Student Name : Piyush Chandrakant Dhebe

PRN: 125UAD1244

Class/Division: SY-AIDS-C

Course Name: Object Oriented Programming using C++

Unit: I






# Smart Home Device Manager

## 📌 Project Overview

**Smart Home Device Manager** is a simple C++ mini-project that models and manages smart devices in a home.

The system represents devices such as **Lights, Thermostats, Cameras, and Door Locks**. Each device stores its basic information and allows its status to be changed. The project also displays an overall **Smart Home Dashboard**.

This project is developed as a **Unit I C++ OOP Mini-Project** to understand and apply basic Object-Oriented Programming concepts.

---

## 🎯 Objectives

* To create a simple smart home management system.
* To store information about different smart devices.
* To switch devices ON or OFF.
* To change the status of a device.
* To store the last-updated time of each device.
* To display all devices using a home dashboard.
* To understand basic OOP concepts in C++.

---

## ⚙️ Features

The program provides the following features:

* Add multiple smart devices.
* Store a unique device ID.
* Store the device type.
* Store the device location.
* Store the current device status.
* Store the last-updated time.
* Switch a device ON.
* Switch a device OFF.
* Change the status of a device.
* Display all devices on the Smart Home Dashboard.
* Display updated device information.

---

## 🏠 Devices Included

The example program contains four smart devices:

| Device ID | Device     | Location    | Initial Status |
| --------- | ---------- | ----------- | -------------- |
| D001      | Light      | Living Room | OFF            |
| D002      | Thermostat | Bedroom     | ON             |
| D003      | Camera     | Main Door   | ON             |
| D004      | Door Lock  | Main Door   | LOCKED         |

---

## 🧠 OOP Concepts Used

| OOP Concept                  | Implementation                                |
| ---------------------------- | --------------------------------------------- |
| Class                        | `SmartDevice` class                           |
| Objects                      | Individual smart devices                      |
| Encapsulation                | Device data is kept private                   |
| Constructor                  | Initializes device information                |
| Constructor Initializer List | Initializes class data members                |
| Member Functions             | `switchOn()`, `switchOff()`, `changeStatus()` |
| `const` Member Function      | `displayData()`                               |
| Vector                       | Stores multiple `SmartDevice` objects         |

---

## 🔧 Technologies Used

* **Language:** C++
* **Libraries:** `<iostream>`, `<string>`, `<vector>`
* **Compiler:** GCC / MinGW / Visual Studio / Code::Blocks
* **C++ Standard:** C++11 or later

---

## ▶️ How to Run

### 1. Save the program

Save the source code as:

```text
SmartHomeDeviceManager.cpp
```

### 2. Compile the program

Using GCC:

```bash
g++ SmartHomeDeviceManager.cpp -o SmartHomeDeviceManager
```

### 3. Run the program

On Windows:

```bash
SmartHomeDeviceManager.exe
```

On Linux/macOS:

```bash
./SmartHomeDeviceManager
```

---

## 📊 Sample Output


=== Smart Home Dashboard ===
ID:D001|Type:Light|Location:Living Room|Status:OFF|Last Updated:08:00
ID:D002|Type:Thermostat|Location:Bedroom|Status:ON|Last Updated:08:05
ID:D003|Type:Camera|Location:Main Door|Status:ON|Last Updated:08:10
ID:D004|Type:Door Lock|Location:Main Door|Status:LOCKED|Last Updated:08:15

=== Updated Home Dashboard ===
ID:D001|Type:Light|Location:Living Room|Status:ON|Last Updated:09:00
ID:D002|Type:Thermostat|Location:Bedroom|Status:ON|Last Updated:08:05
ID:D003|Type:Camera|Location:Main Door|Status:ON|Last Updated:08:10
ID:D004|Type:Door Lock|Location:Main Door|Status:UNLOCKED|Last Updated:09:05

---

## 📁 Project Structure


Smart-Home-Device-Manager/
│
├── program.cpp
│
└── README.md




## 📚 Learning Outcome

After completing this project, the learner can understand how basic C++ OOP concepts can be applied to a real-world problem.

The project provides practical experience with:

* Classes and objects
* Constructors
* Private data members
* Public member functions
* Vectors of objects
* Status management
* Data display
* Basic real-world system modeling

---

## 👨‍💻 Author

**Piyush Dhebe**

**C++ Unit I Mini-Project**

**Project:** Smart Home Device Manager
