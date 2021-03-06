![logo](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/GGL_logo.png)

# GGL-Documentation

GML GUI Library (GGL), Written by Ced30.

# Welcome to GGL!

**GGL** is a graphical user interface library for Game Maker Studio v2.3+,
It's made with ease of use in mind, mainly to quickly build **GUI** for your **games** and **tools**. 
The **GUI** elements are composed of gameObjects (parents) and structs (children).

You CAN use it in any of your projects, commercial or not, you CANNOT redistribute it,
not by itself nor as part of a project you want to distribute.

If you don't own **GGL**, you can download an try the demo [**here**](https://github.com/Ced30/GGL-Documentation/tree/main/Demo)


## Description

**GGL** supports Game Maker Studio2 versions 2.3 and above. 

**What the package contains:**
- 1 Controller object
- 1 Event_manager object
- a collection of parent_GGL elements
- a collection of GGL_sub elements
- a collection of prefab_GGL elements
- a collection of factory scripts
- a collection of wrapper scripts
- a collection of sprites
- a collection of sounds
- a tweening controller
- an implementation of Vector2, Vector3 (incomplete) and Rectangle classes
- 11 demo rooms

**Features of the Controller object:**
- Instance destruction
- Keeps track of which button is currently selected
- Mouse input variables
- Z-order

**Features of the Event_Manager object:**
- Handles the events that you can fire or register to (greatly simplifies elements interaction)


## Important

- GGL GUI elements are divided in 2 categories, parents and childrens, the parents, are objects that you can drag into the room, and the children, are structs that must be added to a container parent.

**Controller:**
- **"obj_GGL_controller"** must be the first GGL instance in the room, as it keeps track of the other instances and draws them.


**Object Destruction:**
- You **must avoid using** the "instance_destroy()" command to destroy a parent element, use the "Expire()" method instead, the controller object will handle the parent's destruction.

## Installation:

- [**Instructions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Installation/instructions.md)


## The fonts used in this package are free to download here:
- [neon 80s](https://www.dafont.com/neon-80s.font)
- [neon 2 news](https://www.dafont.com/neon-2-news.font)


## Quick Start

- [**Room Setup**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Quick%20Start/Room_Setup.md)
- [**Instancing parent_GGL objects**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Quick%20Start/Instancing_parent_GGL%20objects.md)


- [**How to setup your first button?**](https://github.com/Ced30/GGL-Documentation/blob/main/Tutorial/Tutorial_First_Button.md)
- [**How to use events?**](https://github.com/Ced30/GGL-Documentation/blob/main/Tutorial/Tutorial_Events.md)
- [**How to create a menu?**](https://github.com/Ced30/GGL-Documentation/blob/main/Tutorial/Tutorial_Menus.md)

## API

Only the **relevant functions**, which would be **public** in an object oriented language will be documented for now.

**Classes:**

- [**Instance Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)

- [**Instance Prefabs**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)

- [**Struct Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)

- [**Struct Prefabs**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct_Prefabs.md)

**Classes Methods:**

- [**Common methods**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Common_Methods.md)

**Functions:**

- [**Factory Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Factory%20Functions.md)

- [**GGL_Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/GGL_Functions.md)

**Controller:**

- [**Controller Functions**](https://github.com/Ced30/GGL-Documentation/blob/main/API/Controller_Functions.md)

**Event_Manager:**

- [**Event Manager Funtions**](https://github.com/Ced30/GGL-Documentation/blob/main/API/Event_Manager_Functions.md)

## Inheritance map

- [**UML Diagrams**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Diagrams/Inheritance.md)

