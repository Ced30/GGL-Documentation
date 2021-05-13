# **Tutorial: setting up your first button using events**

Lets see how to make something simple using a toggle to group / ungroup a couple of other GUI elements.

- **1 - Create the room**:

For the sake of the example, We will create a room with a width of 1280, a height of 720, same for the viewport and window size, just like this:

![room](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/room.png)


- **2 - Drag the controllers into the room**

Drag a GGL controller first and a GGL Event Manager into the room, as the other elements cannot function witout them

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/Controllers.png)


- **3 - Create the toggle**:

Then, grab a parent_GGL_toggle in the asset manager, drag it into the room, and by clickng on the "variables" tab, you can edit the label to begin with

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/toggle1.png)

- **4 - Create the script that will fire the event**:

In a script file, we'll write the "Toggle_the_group" function, that we will pass to the toggle.

Once the toggle has been clicked, it's "toggled" variable will change and the toggle will run this function and fire the event,
so, we pass the id of the event as 1rst argument and the "toggled" variable as 2nd argument.

![toggle](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/Tutorial/Events/script_fire.png)

- **5 - pass the script to the toggle**
Go back to the room, and scroll through the instance's variables until you find "Script_Activate", paste the name of the function you created there.

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

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/README.md)
