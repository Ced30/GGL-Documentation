# Class parent_GGL_dropdown

You can setup the sub buttons either by code, after inheriting from this parent, with the "Add_element"	method, 
or pass an array of to the "labels_sub_buttons" variable,	and passing a function to the "script_sub_buttons" variable.
(after placing this instance in a room, go to the variable definitions).

The buttons are then created in the "Initialize" method.
	
**Important:**
	
- By inheriting from this parent, you can have 1 function per	GGL_sub button.
  
- By setting things up after placing this instance into a room and tweaking the variable definitions, you can have only 1 function
	  common to all the GGL_sub buttons.
	
The GGL_sub buttons stay hidden until "elements_active" is set to true,
if you click outside of the dropdown, it will close itsef.

# Relevant Methods

N/A

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_dropdown.png)

**buttons_spacing**	 => the vertical spacing between buttons (multiplicated by the y scale).

**labels_sub_buttons** => an array of string labels to setup the GGL_sub buttons array without the need to inherit from this parent (ex: ["item0", "item1", "item3".. etc])

**script_sub_buttons** => a script common to all of the GGL_sub buttons created with the "labels_sub_buttons" variable.

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
