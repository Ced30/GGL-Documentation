# **Tutorial: setting up your first button using events**

Lets see how to make something simple using a toggle to group / ungroup a couple of other GUI elements.

- **1 - Create the room**:

For the sake of the example, We will create a room with a width of 1280, a height of 720, same for the viewport and window size, just like this:

![room](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/room.png)

- **2 - Create the toggle**:

Then we grab a parent_GGL_toggle in the asset manager, drag it into the room, and by clickng on the "variables" tab, we can edit the label to begin with

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/toggle1.png)

- **3 - Create the script that will fire the event**:

In a script file, the write the "Toggle_the_group" function, that we will pass to the toggle.

Once the toggle has been clicked, it will run this function and fire the event.

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/script_fire.png)

- **4 - pass the function to the toggle**
Go back to the room, and scroll through the instance's variables until you find "Script_execute", paste the name of the function you created there.

![pass_the_func](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/pass_the_function.png)

- **5 - Create the script that the buttons will run once the toggle is clicked**

![button](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/script_when_toggled.png)

It's a simple script, it receives a boolean in parameters, and sets the instance that runs this script active with this boolean as parameter

- **6 - Drag a bunch of instances of this button in the room**

Once we dragged a bunch of them, set their "active" variable to false, set their label how you want, then, in their create event, register to the event we created earlier.

![buttons2](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/drag_the_buttons.png)
