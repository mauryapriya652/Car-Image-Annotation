# Car-Image-Annotation

Car Image Annotation is a Python-based project used to create bounding box annotations for car images. It helps prepare datasets for object detection and computer vision models such as YOLO.

## Features

- Annotate car images manually
- Draw bounding boxes using the mouse
- Save annotations in YOLO format (.txt)
- Supports multiple images
- Easy to use with OpenCV

## Folder Structure

Car-Image-Annotation/
│── images/
│── annotate.ipynb
│── README.md
│── .gitignore


## Requirements

- Python 3.x
- OpenCV

Install the required package:

```bash
pip install opencv-python
```

## How to Run

1. Open `annotate.ipynb` in  VS Code.
2. Run all cells.
3. Draw bounding boxes on each car image.
4. Annotation files will be saved automatically in the `annotations` folder.

## Output

- Annotated images
- YOLO annotation files (`.txt`)
