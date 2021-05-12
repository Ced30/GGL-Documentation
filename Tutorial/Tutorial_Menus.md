# **Tutorial: setting up your first button using events**

Lets see how to make something simple using a toggle to group / ungroup a couple of other GUI elements.

- **1 - Create the room**:

For the sake of the example, We will create a room with a width of 1280, a height of 720, same for the viewport and window size, then, we drag
a GGL_controller into the room and somewhere in a script file, we create an enum to hold the indexes of the pages of our menu.

![room](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/Menu_room.png)

- **2 - Open the "Creation code of your parent_GGL_menu once it's in the room"**:

Then we will declare some variables to simplify our task.

The coordinates of your GGL_sub elements are relative to the coordinates of the container instances, meaning, the parent_GGL_menu always positions itself at the center of the GUI, so, it's coordinates are the 0, 0 coordinates of the GGL_sub.

Example, if you want a GGL_sub at the center of the GUI, it's coordinates will be x = 0, y = 0

![toggle](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/declarations.png)

- **4 - Create the script that will fire the event**:

In a script file, the write the "Toggle_the_group" function, that we will pass to the toggle.

Once the toggle has been clicked, it will run this function and fire the event.

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/script_fire.png)

- **5 - pass the script to the toggle**
Go back to the room, and scroll through the instance's variables until you find "Script_execute", paste the name of the function you created there.

![pass_the_func](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/pass_the_function.png)

- **6 - Create another script, that the buttons will run once the toggle is clicked**

![button](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/script_when_toggled.png)

It's a simple script, it receives a boolean in parameters, and sets the instance that runs this script active with this boolean as parameter

- **7 - Drag a bunch of instances of this button in the room**

Once we dragged a bunch of them, set their "active" variable to false, set their label how you want, then, in their create event, register to the event we created earlier.

![buttons2](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/drag_the_buttons.png)

- **8 - Test your 1rst creation!**

The buttons receive the event they registered to when the toggle is clicked, and they run their script to set active / inactive, congratz, you used your first events!

![buttons2](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/Tuto1_complete.gif)



