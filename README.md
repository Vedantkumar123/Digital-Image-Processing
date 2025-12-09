# Digital‑Image‑Processing

A set of Python scripts exploring and implementing a variety of classic digital image processing techniques — my playground for learning fundamental computer vision and image processing concepts using OpenCV and other Python tools.

## 📚 What this repo contains

* Scripts that implement core image processing operations — filtering, thresholding, contour detection, perspective transforms, warping, morphological operations, and more.
* Utility functions to help with repeated tasks (e.g. stacking images for display, contour selection, image warping / ROI extraction).
* Experiments in reading, transforming, preprocessing, and extracting information from images — useful when building higher-level applications with computer vision.
* A learning‑oriented structure: these are not full “products” but intentionally modular, commented, and exploratory — designed to help me understand what’s happening under the hood when an algorithm touches the pixel data.

## 🔧 Why I built it — My learning goals

* To get a strong practical understanding of what happens inside basic image processing algorithms: noise reduction, edge detection, warping, perspective correction, contour detection and extraction.
* To build confidence reading and manipulating raw image data as arrays (without relying only on high-level abstractions).
* To have a sandbox where I can test and visualize intermediate steps — e.g. see grayscale conversion, thresholding, contour detection results side by side — helping me internalize the “processing pipeline.”
* To create a foundation for more advanced computer‑vision or deep‑learning projects (like segmentation, object detection), by first mastering the fundamental building blocks.

## 🧪 What’s inside (highlights)

* Functions for stacking multiple image views side-by-side — helpful for comparing original, processed, thresholded, contoured, warped versions of the same image.
* Contour detection & selection logic: ability to find the largest contour, approximate it to a polygon, warp perspectives — useful for document scanning / ID‑card detection applications.
* Preprocessing routines: image smoothing, adaptive thresholding, noise reduction — to ensure better output when doing OCR or further computer vision tasks.
* Image cropping / ROI extraction methods: ability to isolate regions of interest (e.g. part of an ID card) for further processing.
* Demonstrations combining several operations into workflows (e.g. read image → preprocess → find contours → warp → crop → extract ROI) — similar to real‑world pipelines.

## 🧑‍💻 How to use / run

1. Clone the repo.
2. Ensure you have Python installed along with required dependencies (e.g. OpenCV, NumPy, matplotlib, pytesseract if using OCR‑related functionalities).
3. Run any of the scripts to experiment: you’ll see images displayed (original, processed, preprocessed, contour overlays, warps etc.), which helps visualize what each step does.
4. Modify image paths / parameters as needed to test on your own images.

## ✨ Useful for

* Beginners (or intermediate learners) who want to get hands‑on practice with image processing fundamentals.
* People building image‑preprocessing pipelines for OCR, document scanning, ID‑card detection, etc.
* Anyone who wants a lightweight, dependency‑minimal “sandbox” to experiment with pixel‑level operations before moving on to deep learning or more advanced computer vision frameworks.
