## Class prefab_GGL_listing

This prefab is intended to be used to display an array of strings.
		the "parameters" variable must contains the array.
	
Override the specific scripts to implement your logic,
		see the "variables" tab after placing the instance in the room.
	
The prefab comes preloaded with: nothing
									 
The array of strings is drawn on a surface, which is partially hidden with a mask, to scroll through 
the array, you can either :  - use the slider
									           - use the mouse wheel
								
To select an entry, just click on it

## Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

## Set_new_listing(pStringArray)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   pStringArray      | an array of strings  |  array of strings containing the new listing    |

| Returns:  | N/A |
|--         |                             --|

Use this method to update the listing of strings you wanna display by providing a new array of strings

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/prefab_GGL_listing.png)

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)
