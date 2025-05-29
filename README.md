# Music Sheet Detector

This project implements a computer vision pipeline for detecting musical symbols from a scanned or photographed music sheet. It is part of the ROB-UY 3203 Robot Vision course project.

## Project Overview
- Detect staff lines in a music sheet  
- Segment individual notes and symbols  
- Identify and classify different musical elements (e.g., quarter notes, half notes)

## Pipeline
1. Image preprocessing (grayscale conversion, binarization)  
2. Staff line detection using morphological operations  
3. Line removal and segmentation  
4. Symbol extraction and filtering  

## Files
- `Music_sheet_detector.ipynb`: Main Jupyter notebook containing the full image processing pipeline  
- `sample_sheet.jpg`: Example input image used for testing the detector   

## Requirements
- numpy  
- opencv-python  
- matplotlib  

### Install dependencies

```bash
pip install numpy opencv-python matplotlib
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Do-Gon/ROB-UY-3203-Robot-Vision-Project.git
cd ROB-UY-3203-Robot-Vision-Project
```

2. Open the notebook:

```bash
jupyter notebook Music_sheet_detector.ipynb
```

3. Run the cells to see the detection pipeline in action.
