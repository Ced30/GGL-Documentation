# Class parent_GGL_list

A list container using buttons GGL_sub buttons, you can setup the sub buttons either by code, after inheriting from this parent, with the "Add_element"	method, 	
or pass an array of to the "labels_sub_buttons" variable,	and passing a function to the "script_sub_buttons" variable.
	(after placing this instance in a room, go to the variable 	definitions).
  
The buttons are then created in the "Initialize" method.
	
**Important:**
	
- By inheriting from this parent, you can have 1 function per GGL_sub button.
	  
- By setting things up after placing this instance into a room and tweaking the variable definitions, you can have only 1 function common to all the GGL_sub buttons.

- **when clicking on a sub button, it's label is stored in the "value" variable**
	
The GGL_sub buttons stay hidden until "elements_active" is set to true, if you click outside of the dropdown, it will close itsef.

# Relevant Methods

## Add_element(label, script)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   label     | string  | the label of the sub button that will be created |
|   script     | script id  | the "Activate" function of sub button created |

| Returns:  | the button that's been created |
|--         |                             --|

Use this method to add new buttons manually.

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_list.png)

- **buttons_spacing**	 => the vertical spacing between buttons (multiplicated by the y scale).

- **labels_sub_buttons** => an array of string labels to setup the GGL_sub buttons array (ex: ["item0", "item1", "item3".. etc]), set it to -1 if you don't use it.

- **script_sub_buttons** => a script common to all of the GGL_sub buttons created with the "labels_sub_buttons" variable, set it to -1 if you don't use it.

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
