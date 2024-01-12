# Siftrama: A Panorama Stitching MATLAB App Using the SIFT Algorithm

## Overview

This MATLAB application provides an intuitive interface for stitching multiple images together to create a panoramic view. Utilizing the Scale-Invariant Feature Transform (SIFT) algorithm, the app allows users to select and upload a series of images. Subsequently, it computes the optimal alignment between these images and generates a seamless panorama.

## Features

- **Image Upload**: Users can upload multiple images that they wish to stitch together.
- **SIFT Parameter Adjustment**: Users can modify SIFT parameters such as Contrast Threshold, Edge Threshold, Layers Per Octave, and Sigma to fine-tune the stitching process.
- **Panorama Generation**: Once the images are uploaded and parameters set, the app automatically generates the stitched panorama.
- **Image Saving**: Users have the option to save the generated panorama in PNG or JPEG format.

## SIFT Parameters

The app allows users to adjust the following SIFT parameters:

1. **Contrast Threshold**: A threshold used to filter out weak features in low-contrast regions. Range: [0, 1].
2. **Edge Threshold**: A threshold used to filter out unstable edge-like features. Range: ≥ 1.
3. **Layers Per Octave**: The number of layers in each octave, which affects feature detection at different scales. Range: ≥ 1.
4. **Sigma**: The Gaussian blur parameter influencing the scale at which SIFT operates. Range: [1, 2].

## How to Use

1. **Upload Images**: Click on the "Upload Images" button to select and upload the images you want to stitch.
2. **Adjust Parameters**: Use the sliders provided to adjust the SIFT parameters as desired.
3. **Generate Panorama**: Click on the "Stitch Images" button to generate the panoramic image.
4. **Save Panorama**: Once the panorama is generated, click on the "Save Image" button to save it to your desired location.

## Notes

- Ensure that at least two images are uploaded for stitching.
- Experiment with SIFT parameters to optimize the stitching results.

## Contributors

- Abdel Rahman Alsabbagh
- Subhi Abdalla
- Ahmad Al Munayyer
