# kubernetes-diagram-builder

This is used to build a kubernetes architecture diagram for the kubernetes challenges hosted on kodekloud.com

The idea is to build a diagram using the UI and export the diagram in a JSON format, to be later used by the kubernetes challenge builder.

# Instructions

- Go to [https://mmumshad.github.io/kubernetes-diagram-builder/](https://mmumshad.github.io/kubernetes-diagram-builder/) to view the diagram builder
- A sample diagram is given.
- The UI is divided into 3 parts. The "Drawing Pad" and "Stencils" at the top. And the "JSON Form" in the bottom.
- Clear the scree by hitting the "clear" button to start afresh.
- Right click on the required icon in the stencils and select "Add". A prompt will appear asking for the item name. Enter the right name. This will add the item to the Drawing Pad.
  Note: There is no rename option. If you want to rename the item later, you must delete and recreate the item.
- To delete the item, right click the item in the Drawing Pad and select "Delete"
- On the Drawing pad, drag the item and move it to the desired place.
- Repeat the procedure to add as many items as required.
- On the Drawing pad, To link an item to another item by drawing an arrow, drag the first item and drop on the second item. This will connect the two items.

- If you want to move the entire graph in different direction, use the "Up", "Down", "Right", "Left" buttons at the top.
- Once the diagram is complete, copy the JSON format from the text box at the bottom and save it. 
- At a later point in time, you may load the same diagram by pasting the exported data back into the JSON Form text box to resume work.
  Note: The work/diagram is not saved automatically. So if the browser is refreshed, the work is lost. Keep a copy of the JSON form periodically.  
