# PILLOW

## Overview

The Python Imaging Library adds image processing capabilities to your Python interpreter.

This library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities.

The core image library is designed for <ins>fast access to data stored in a few basic pixel formats</ins>. It should provide a solid foundation for a general image processing tool.

### Image Archives

The Python Imaging Library is ideal for image archival and batch processing applications. You can use the library to create thumbnails, convert between file formats, print images, etc.

### Image Display

The current release includes Tk `PhotoImage` and `BitmapImage` interfaces, as well as a `Windows DIB interface` that can be used with PythonWin and other Windows-based toolkits. Many other GUI toolkits come with some kind of PIL support.

For debugging, there’s also a `show()` method which saves an image to disk, and calls an external display utility.

### Image Processing

The library contains <ins>basic image processing functionality, including point operations, filtering with a set of built-in convolution kernels, and colour space conversions</ins>.

The library also supports <ins>image resizing, rotation and arbitrary affine transforms</ins>.

There’s a histogram method allowing you to pull some statistics out of an image. This can be used for automatic contrast enhancement, and for global statistical analysis.