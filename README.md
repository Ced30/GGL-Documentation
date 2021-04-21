![logo](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/GGL_logo.png)

# GML-GUI-Library-GGL-Documentation

GML GUI Library (GGL), Written by Ced30.

# Welcome to GGL!

**GGL** is a graphical user interface library for Game Maker Studio v2.3+,
It's made with ease of use in mind, mainly to quickly build **GUI** for your **games** and **tools**. 
The **GUI** elements are composed of gameObjects and structs.

## Description

Only the **main functions**, which would be **public** in an object oriented language will be documented for now.
**GGL** doesn't work with a Game Maker Studio2 version older than 2.3.

GGL supports z-order, it uses a controller object (obj_GGL_controller) to draw all of the parent_GGL instances and handle their destruction.

GGL GUI elements have 2 versions, the "parent" version, which is an object you can drag into the room, and the "sub" version, which is a struct and must have an owner (parent).

## Installation

1.  In your GameMaker project, click "Tools" on the top menu.
2.  Select "Import Local  **Package**"
3.  Navigate to the downloaded .**yymp**  file in the file explorer
4.  Double click on the .**yymp**  file.
5.  An "Import Resources" window will open up. ...
6.  Click "Import" (leave the checkbox unchecked)

## Important

**Room Setup:**

The first layers of you room **must be the same** as in the picture below, 
- the first one is a layer reserved to run VFX like vignette, etc (see it in action in the demo rooms),
- the second one **must contain** an instance of **obj_GGL_controller** (mandatory), and finally,
- the third one, will contain all of the rest of you GGL instances.

**obj_GGL_controller** must be **the first GGL object of your instance creation order**, don't put any GUI elements before.

![Room_setup](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/room_setup.png)

**Object Destruction:**

Because of the fact that objects are drawn by the **obj_GGL_controller**, you **must avoid using** the "instance_destroy()" command
to destroy a parent element, use the "Destroy()" method instead, the controller object will handle the parent's destruction.

## Instancing parent_GGL objects

Once you have dragged the parent_GGL object into the room, you can access the main relevant variables by clicking on the object's "variables" tab and override them.

![var_def1](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/variable_definitions2.png)

Else, if the object has not been dragged into the room, you can access it's main relevant variables by clicking on the "variable definitions" tab.

![var_def1](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/variable_definitions1.png)

## Quick Start

- [**Button_example**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)

## API

**Classes:**

- [**Instance Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)

- [**Instance Prefabs**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)

- [**Struct Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)

- [**Common methods**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Common_Methods.md)

**Functions:**

- [**Factory Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Factory%20Functions.md)

- [**GGL_scripts**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/GGL_sub%20Functions.md)

- [**Helper Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Helper_Functions.md)
