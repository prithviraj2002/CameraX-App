# camerax
Demonstrating camerax library's usage and functions

# Project Overview

1) There are two directories, camera and screens.

2) The Camera directory contains three files
  a) preview-image file contains a composable ImagePreview() to display camera preview before capturing an image.
  b) capture-image file contains a composable CaptureImage() which uses the ImagePreview() composable to load a preview, and then captures that preview.
  c) camera-function file contains all the functions necessary for above composables.
  
3) screen directory conatins a single file 'home-screen'.
  a) 'home-screen' contains a composable HomeScreen() which loads the main screen.
  
  # User Interface
  
  1) Permission dialog is prompted
  
![Screenshot_2023-01-15-10-00-47-371_com google android permissioncontroller](https://user-images.githubusercontent.com/82358330/212523495-dfba89e4-1a63-46ee-99f4-dc94b151062c.jpg)

2) Working preview of the app

https://user-images.githubusercontent.com/82358330/212523499-128841ae-2247-40f2-bf5c-4ea2fbdf3ea6.mp4
