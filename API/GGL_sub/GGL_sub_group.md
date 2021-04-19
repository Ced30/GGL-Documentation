# Class GGL_sub_group

"GGL_sub_group" is typically used to build game menus with a "parent_GUI_menu" object as an owner, it can contain other GUI_sub elements such as button, slider, checkboxes, etc.

"mouse_hover" is not checked directly, but is check by the sub elements themselves.	

# Relevant Methods

## Add_element(type, label, script, x, y, w, h, (optional)value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    type     |   type id   |    the type of GGL_sub to add                   |
|    label    |   string   |     the label of the GGL_sub we're adding             |
|    script   |   script id   |    the "Activate" function we're passing         |
|    x        |   real   |     the x position of the GGL_sub relative to the container      |
|    y        |   real   |     the y position of the GGL_sub relative to the container  |
|    w        |   real   |     the width of the GGL_sub  |
|    h        |   real   |     the height of the GGL_sub   |
|    value    |   any type |   stores a value inside "value" (optional argument)   |

| Returns:  | the GGL_sub created |
|--         |                   --|

Use this method to manually add GGL_sub elements to the container, you can pass an optional argument that will be stored in the GGL_sub "value" variable.

# Variable Declarations

- **tween_duration** => how long does the scaling take?
- **wait_duration**  => how long do we wait to be interactable with after scaling?

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
