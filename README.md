# Image Stylization

This repository contains code for image stylization, a technique used to transfer the style of one image onto another image. It implements an algorithm that combines the content of one image with the style of another, producing a stylized version of the content image.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

Image stylization is a popular technique in the field of computer vision and image processing. It allows users to apply the artistic style of one image onto the content of another image. This repository provides an implementation of an image stylization algorithm based on deep learning.

The algorithm utilizes a pre-trained convolutional neural network (CNN) that has been trained on a large dataset of artwork images. It extracts both the content and style information from input images using different layers of the CNN. By optimizing the content and style representations, the algorithm generates a new image that combines the content of one image with the style of another.

## Installation

1. Clone the repository:

   ```bash
   git clone : git@github.com:AJtheDeMoN/Image-Stylization.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Image-Stylization
   ````

## Usage

To stylize an image using the provided algorithm, follow these steps:

1. Make sure you have activated your virtual environment (if applicable).

2. Prepare the content and style images. Ensure that the images are in a compatible format (e.g., JPEG, PNG).

3. Run the stylization script:

   ```bash
   python Image_stylization.py
   ```

   Replace `<path_to_content_image>` with the path to the content image file, `<path_to_style_image>` with the path to the style image file, and `<output_path>` with the desired location and name of the output stylized image.

4. Wait for the script to finish executing. The output image will be saved at the specified `<output_path>`.
