# Class parent_GGL_popup_container

Base popup container with easing and "pop-in" and "pop_out" behavior, it can contain GGL_sub elements of any kind.

# Relevant Methods

## Add_element(type, label, script, x, y, w, h)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    type     |   type id   |    the type of GGL_sub to add                   |
|    label    |   string   |     the label of the GGL_sub we're adding             |
|    script   |   script id   |    the "Activate" function we're passing         |
|    x        |   real   |     the x position of the GGL_sub relative to the container      |
|    y        |   real   |     the y position of the GGL_sub relative to the container  |
|    w        |   real   |     the width of the GGL_sub  |
|    h        |   real   |     the height of the GGL_sub   |

| Returns:  | the GGL_sub created |
|--         |                   --|

Use this method to manually add GGL_sub elements to the container

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_popup_container.png)

- **tween_duration** => the duration of the pop effect
- **desired_width**  => the desired width of the panel when scaled to min	(from 0 to 1, maximum is equal to GUI width)
- **desired_height** => the desired height of the panel when scaled to min (from 0 to 1, maximum is equal to GUI height)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
