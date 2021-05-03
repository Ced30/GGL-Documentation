# Function GGL_group_set_active_ext(pGROUP_ID, pActive)

|  Parameter    |  type   |     description        |
|--             |       --|--                      |
|   pGROUP_ID      | string  | the group id to look for    |
|   pActive      | boolean  | should the group be active?    |

| Returns:  | N/A |
|--         |                             --|

Looks for parent_GGL_instances which have the same "GROUP_ID" as "pGROUP_ID" and sets their "active" variable
Then, looks at all the parent_GGL_containers GGL_sub elements and sets their "active" variable, if the GGL_sub 
"GROUP_ID" is the same as "pGROUP_ID"

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/GGL_Functions.md)
