# Class GGL_sub

The core GGL_sub element, it's not to be used as is, it's intended to be inherited from.
It does nothing by itself, it's just a building block.

# Relevant Methods

none, it holds mainly empty methods that are meant to be overriden.

# Variable Declarations:

- **alpha_max**         => the maximum alpha value
- **alpha_modifier**    => use it to modify the alpha interpolations
- **active**            => true;
- **debug**             => false;
- **interactive**       => true;
- **mouse_hover**       => false;
- **owner**             => the instance containing this GUI_sub.
- **scale_increase**    => how much does it increase in scale from min to max?
- **scale_max**         => the maximum scale of the GGL_sub
- **scale_min**         => the minimum scale of the GGL_sub
- **alpha_modifier**    => use it to modify the scale interpolations
- **scale_relative**    => the scale relative to size of the sprite index and the minimum scale of the instance (from 0 to 1).
- **scale_zero**        => a vector2 with x and y = 0
- **speed_scale_in**    => the speed of the scaling when it appears or "mouse_hover" is set to true
- **speed_scale_out**   => the speed of the scaling when it disappears or "mouse_hover" is set to false
- **state_GGL**         => the current state of the state machine				
- **position_relative** => the position of this instance relative to it's owner's position

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct_Prefabs.md)
