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
