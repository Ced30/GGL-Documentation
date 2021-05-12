# Class GGL_sub_draggable

Same as GGL_sub_button, except, you can drag it across the room if the mouse is above the button and left click is maintained.

# Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

## Get_value()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  N/A  |   N/A   |  N/A    |

| Returns:  |  the "value" variable, which can store any type of value |
|--         |                                                        --|

Returns the "value" variable

## Set_value(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_value  |   any   |  this variable can store any type of value    |

| Returns:  |         N/A |
|--         |                             --|

Stores any kind of value inside the "value" variable (this in conjonction with the "Activate" function can make each button unique in functionality)

# Variable Declarations:

- **distance** => the distance from the position of the instance and the mouse GUI position
- **dragged**  => is the instance dragged?

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
