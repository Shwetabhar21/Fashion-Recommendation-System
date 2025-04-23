# Fashion Recommendation System

This project is a starting point for a fashion recommendation system. It currently extracts and displays images from a dataset, which is a crucial first step in building a system that can recommend fashion items.

## Project Description

The goal of this project is to develop a system that can recommend fashion items to users.  The initial steps involve:

1.  **Data Extraction**: Extracting image data from a zip file.
2.  **Data Exploration**:  Displaying sample images to understand the dataset's characteristics.

##  File Structure

* `Fashion_Recommendation_System.ipynb`:  Jupyter Notebook containing the code.
* `women-fashion.zip`:  (Assumed) Zip file containing the fashion image dataset.
* `women_fashion/`: Directory where the zip file is extracted.
* `glamorous two-piece outfit featuring a sequined design.jpeg` etc: Sample image files.

## Requirements

* Python 3
* Libraries:
    * `zipfile`
    * `os`
    * `PIL` (Python Imaging Library)
    * `matplotlib`

## Analysis

The project focuses on the initial steps of a fashion recommendation system:

* **Data Extraction**: The notebook extracts image data from the `women-fashion.zip` file.
* **Data Exploration**: The notebook displays sample images from the extracted data.
* **Image Recommendation**: If the user provides an image from outside the dataset, the system can still use the images within the dataset to provide recommendations.
