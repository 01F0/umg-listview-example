# umg-listview-example
A simple example on how to set up a UMG ListView with custom properties in Unreal 4.

# How to run it
Open ListViewMap and press play. It should show you a ListView with two items.

1. The level blueprint will add the W_Fruit_List widget to the viewport. 

2. The W_Fruit_List widget adds a few objects (BP_Fruit_Data_Entry) to its ListView property. 

3. The ListView will create a new instance of the defined entry class (W_Fruit_Presentation_Widget)

3. W_Fruit_Presentation_Widget implements the **On List Item Object Set** method and will transfer the data from BP_Fruit_Data_Entry to the TextBlock in W_Fruit_Presentation_Widget.
