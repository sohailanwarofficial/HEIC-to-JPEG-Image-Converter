# HEIC to JPEG Image Converter

This project provides a Python script for converting HEIC (High-Efficiency Image File Format) images to JPEG format. HEIC is a modern image format that offers high-quality compression, but it may not be supported by all devices and software. This converter allows you to easily convert HEIC images to a more widely compatible JPEG format. This README provides an overview of the code and its usage.

## Overview

The provided script performs the following tasks:

1. Installs the necessary Python packages (pyheif and pillow) for HEIC image handling.
2. Specifies the directory containing HEIC images to be converted.
3. Specifies the directory where the converted JPEG images will be saved.
4. Iterates through HEIC files in the specified directory, converts them to JPEG, and saves them in the output directory.

## Getting Started

Before running the code, ensure that you have:

1. HEIC images stored in a directory (e.g., 'dataset-2/Backward') on your Google Drive.
2. Python installed on your local machine or Google Colab.
3. Installed the required packages (pyheif and pillow) using the provided installation commands.

## Customization

You can customize the code to fit your specific needs:

1. Modify the `heic_images_dir` variable to specify the directory containing your HEIC images.
2. Change the `jpeg_images_dir` variable to set the output directory for converted JPEG images.
3. Adjust the file extensions (e.g., '.HEIC' and '.JPG') to match the format of your images if necessary.

## Conversion Performance

The code utilizes the 'pyheif' library to read HEIC images and the 'pillow' (PIL) library to save them in JPEG format. The conversion performance may vary depending on the number and size of your HEIC images.

## Usage Notes

Ensure that your HEIC images are correctly organized and labeled in the input directory. The script will replace the '.HEIC' extension with '.JPG' for the converted images.

If you encounter any issues or have questions, feel free to reach out for assistance.

Enjoy converting your HEIC images to JPEG format with ease!
