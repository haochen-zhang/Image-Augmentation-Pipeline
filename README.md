# Image-Augmentation-Pipeline
An image augmentation pipeline with customized data for AR education

## Table of Contents
- Background
- Usage
- Contributors
- Further Information

## Background

## Install

This project is implemented with Google Colab. Please download all the files and upload them into your own Google Drive project folder and then open it.

## Usage

The camera calibration part of the project is built on April Group's work, for detailed information, please see <a href="https://april.eecs.umich.edu/wiki/Camera_suite"> April Robotics Laboratory. </a>

First you need to change the project path to your working folder path.

``` sh
# Set target path on Google Drive. 
# Change this location if desired, but make sure it exists.
%cd "Your project folder address on Google Drive"
```

Second, you should import your working images and change the image path accordingly wherever the program tries to read image.

```sh
# image with two AprilBoards (fine and coarse)
fname='image path'
```

The project supports simple geometry rendering, you can adjust the size, position and amount of geometries by changing the code under 5.1 section.

The project also supports simulatvie Lambertian lighting, you can adjust parameters by changing the code under 6.1 section.

## Contributors

<a href="https://github.com/QuinnHe"><img src='https://avatars.githubusercontent.com/u/31847981?v=4' height="40" width="40"></a>
