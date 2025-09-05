# Red-blood-cells-RBC-counts-from-blood-vessel-capillary
We are counting the number of RBCs traveling through a single capillary blood vessel using a two-photon imaging modality. A red dye (Texas Red, 70 kD) is used to label the vessel wall.

In this example, the RBC count is based on black and white lines. The code counts the number of white lines, which is ideally n+1 relative to the number of black lines under clear and short-duration imaging conditions. However, over a longer duration—say 20 to 30 minutes—missing a few RBCs may not significantly affect the results.

The code uses .tiff images and crops the segment where the lines are visible(Imagej is used for x,y location to crop). It’s a simple but usefull approach, especially in cases where the lines are clear and there is minimal overlap. The example includes output counts and a sample image.

The code is annotated with comments to explain each operation.
