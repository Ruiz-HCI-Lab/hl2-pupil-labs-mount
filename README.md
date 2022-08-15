# HL2 Pupil Labs Mount

3D printed mount for Pupil Labs attachment on HoloLens 2. This mount requires the Pupil Labs Hololens Binocular Add-on.

## Files

```.blend``` files are the Blender source files. Blender 3.3.0 was used to create the models.
```.stl``` files are the exported 3d models for printing. Import these into your 3d slicer software.
```.gcode``` files are compiled with QIDI print (including supports) and are ready for printing on a gcode compatible printer.

* ```hl2_pupillabs_mount_<version>```: source file for different mount designs. Use the latest version.
* ```hl2_pupillabs_mount_<version>_print```: clean models, arranged for printing.
* ```pupillabs_connector```: high quality version of the triangular connector that attaches to the Pupil Labs camera.

## Printing

Use the ```.gcode``` file if present or import the latest ```.stl``` to your 3d slicing software.
Supports are needed ("gyroid" pattern is recommended, but others should work).
20-25% infill gives good results. Higher values may cause the mount or screws to break.
Use self-tapping micro screws (size M1.7*5) to attach the two parts of the mounts together on the headset.
