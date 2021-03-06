## Class prefab_GGL_listing_files

This prefab is intended to be used to list files.
the "parameters" variable contains an array of strings which represent the names of the files.

Override the specific scripts to implement your logic, see the "variables" tab after placing the instance in the room.

## Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

## Add_entry()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Implement your own method to add an entry to the data structure containing the entries.

## Remove_entry()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Implement your own method to remove the entry	from the data structure it's stored in

## Rename_entry()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Implement your own method to rename the entry	inside the data structure it's stored in

## Save_entries()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Implement your own method to save the entry inside the data structure it's stored in

## Select_entry()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Selects the current entry based on mouse GUI position, then, sets the string contained inside the "value" variable of the text input box and update the position of the slider

## Set_new_listing(pStringArray)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   pStringArray      | an array of strings  |  array of strings containing the new listing    |

| Returns:  | N/A |
|--         |                             --|

Use this method to update the listing of strings you wanna display by providing a new array of strings

## Switch_indexes()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Implement your own method to save the switch 	the selected entry and the one below / above


# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/prefab_GGL_listing_files.png)

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)
