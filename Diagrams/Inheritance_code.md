```mermaid
graph LR
A[parent_GGL] --> B[parent_GGL_label] --> C[parent_GGL_panel] --> D[parent_GGL_button]
C[parent_GGL_panel] --> AF[prefab_GGL_shader_panel]
C[parent_GGL_panel] --> AG[prefab_GGL_vignette]
D[parent_GGL_button] --> E[parent_GGL_draggable]
D[parent_GGL_button] --> F[parent_GGL_grabbable]
F[parent_GGL_grabbable] --> H[parent_GGL_grabbable_animated]
E[parent_GGL_draggable] --> N[parent_GGL_slider_H] --> 
AB[prefab_GGL_box_slider_H]

N[parent_GGL_slider_H] -->  AA[parent_GGL_slider_V] --> AC[prefab_GGL_box_slider_V]
E[parent_GGL_draggable] --> G[parent_GGL_draggable_animated]
D[parent_GGL_button] --> I[parent_GGL_maintainable]
D[parent_GGL_button] --> J[parent_GGL_toggle]
J[parent_GGL_toggle] --> K[parent_GGL_toggle_linked]
D[parent_GGL_button] --> L[parent_GGL_text_input_box]
D[parent_GGL_button] --> M[parent_GGL_bar_H] --> AK[parent_GGL_bar_V]
D[parent_GGL_button] --> O[parent_GGL_container] --> AJ[prefab_GGL_container_panel]
O[parent_GGL_container] --> AD[prefab_GGL_color_palette]
J[parent_GGL_toggle] --> P[parent_GGL_checkbox]
S[parent_GGL_dropdown] --> T[parent_GGL_list]
O[parent_GGL_container] --> S[parent_GGL_dropdown]
O[parent_GGL_container] --> R[parent_GGL_popup_container]
O[parent_GGL_container] -->AE[prefab_GGL_listing] --> AH[prefab_GGL_listing_files] --> AI[prefab_GGL_listing_layers]
R[parent_GGL_popup_container] --> W[parent_GGL_popup_message]
R[parent_GGL_popup_container] --> V[parent_GGL_window] 
R[parent_GGL_popup_container] --> U[parent_GGL_textbox]
O[parent_GGL_container] --> Q[parent_GGL_menu]


V[parent_GGL_window] --> Z[prefab_GGL_windows_value_return]
V[parent_GGL_window] --> X[prefab_GGL_popup_CONFIRM_CANCEL]
V[parent_GGL_window] --> Y[prefab_GGL_window_with_confirmation]
