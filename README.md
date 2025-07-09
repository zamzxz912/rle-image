# RLE Image Compressor

## Overview

RLE Image Compressor is an Android application that allows users to compress and decompress images using the Run-Length Encoding (RLE) algorithm. The application provides a simple interface for selecting images, applying compression with different processing modes, exporting compressed data as `.rle` files, and restoring images from previously saved compressed files.

This application is developed with a focus on client-side performance, portability, and offline usability. All image processing and file handling is performed directly on the user's device without the need for internet connectivity.

## Features

- Select images from device storage
- Apply image compression using Run-Length Encoding
- Three compression modes:
  - RGB: preserves full color data
  - Grayscale: reduces image to intensity values
  - Threshold: converts image to black and white
- Export compressed data to `.rle` file format
- Import and decompress `.rle` files
- Preview original and decompressed images
- Display compression metadata:
  - Image dimensions
  - Original and compressed file sizes
  - Compression ratio
- Works entirely offline

## Requirements

- Android 7.0 (API level 24) or higher
- Storage permission (for file import/export)

## Technologies Used

- Kotlin / Java (Android SDK)
- Android Jetpack components
- Image processing with `image` package
- File access with `file_picker` and `permission_handler`
- UI built using standard Android Views and Widgets

## Contributors
- Zamiel Alfaro Davido Mahoro (me)
- Jesika
- Rohana Labora Munthe
- Putri Angel
- Angela Steffani Agatha Sitanggang
