# 3D Models Folder

Each 3D-model is saved as an individual file. For KiCAD it has to be either a `.stp`-file or a `.wrl`-file.

To add new 3D-model to the project 3D-model library:
- Download and save the 3D model (`.stp` or `.wrl`-file) under `lib/3d_models`
- In the **Footprint Editor**, select the footprint from the **Library Tree** (list on left side), and then click on the **Footprint Properties...**-button.
- Then in the **Footprint Properties**-window, choose **3D Models** and click on **+** and then the folder-icon to choose the model you added under the `lib/3d_models`-folder.


## Additional Note(s)

- To move components from the **Schematic Editor** to the **PCB Editor** you have to open the **PCB Editor**, and then open the **Update PCB from Schematic (F8)**-window.
- To see how the 3D-models and the PCB will look like, open the **3D Viewer (Alt+3)**.


More info: https://kicad.github.io/packages3d/

