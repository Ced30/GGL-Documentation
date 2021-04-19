# Class parent_GGL_popup_message

This is a popup panel with a label, poping-in, staying for a set duration, and poping-out to be destroyed.
  
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

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_popup_message.png)

- **tween_duration** => how long does the tweenning effect take?
- **wait_duration**  => how long the panel stays on screen?
- **sprite_bg**      => sprite for the background (a stretched and colored pixel covering the screen)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
