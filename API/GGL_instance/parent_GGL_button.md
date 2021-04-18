# Class parent_GGL_button

default button, can be interacted with to by left 
clicking while the mouse is above the button,
to call the "Activate" method.
  
The "Activate" method can be overriden by "Activate_override" to 
replace the "Activate" method.
  
# Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

# Get_value()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  N/A  |   N/A   |  N/A    |

| Returns:  |  the "value" variable, which can store any type of value |
|--         |                                                        --|

# Set_value(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_value  |   any   |  this variable can store any type of value    |

| Returns:  |         N/A |
|--         |                             --|

Stores any kind of value inside the "value" variable (this in conjonction with the "Activate" function can make each button unique in functionality)

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_button.png)

**sound_active**      => the sound played when you interact with the button

**sound_hover**       => the sound played when the mouse is above the button

**sound_inactive**    => the sound played when you drop a draggable or grabbable object

**Activate_override** => override (replace) the "Activate" method.

**value**             => custom data storage, use if for what you want (i use it in menu buttons to store room names and change room with a function)

**color_value1**      => the color of the "value" text drawn (top)

**color_value2**      => the color of the "value" text drawn (bottom)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
