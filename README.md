# Computer Vision (PG-DUASP) - Lab Assignments by Tushar B. Kute

This repository contains the practical lab assignments and code examples for the **Computer Vision (PG-DUASP)** course. The code is written in Python using Jupyter Notebooks (`.ipynb`) and primarily utilizes the OpenCV and Matplotlib libraries.

The main objective of this course and repository is to introduce students to the fundamentals of Computer Vision.

## Prerequisites

A good working knowledge of the following is recommended:
* Python Programming
* Mathematics (Linear Algebra)

## 🛠️ Setup and Installation

To run the notebooks in this repository, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Install the required libraries:**
    It is highly recommended to use a virtual environment. This repository includes a `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```
    *If you prefer to install manually, the main packages are:*
    ```bash
    pip install opencv-python matplotlib jupyterlab
    ```

3.  **Run Jupyter Lab:**
    ```bash
    jupyter lab
    ```
    This will open a new tab in your browser where you can navigate to and run the `.ipynb` files.

## 📓 Repository Structure & Syllabus

The repository is organized by session, mirroring the 10-session structure of the course. Each notebook contains practical implementations of the topics covered in the corresponding theory session.

| Session | Topics Covered | Notebook File (Suggested) |
| :--- | :--- | :--- |
| **01** | Introduction to CV, Loading, Displaying & Saving Images, Grayscale vs. Color, BGR vs. RGB, `cmap` | `01_Image_Basics.ipynb` |
| **02** | Image & Video Basics, Pixels, Coordinate Systems, Pixel Manipulation, Video Capturing & Playing | `02_Video_Basics.ipynb` |
| **03** | Drawing Functions (Lines, Rectangles, Circles), Annotating Images, Mouse as a Paintbrush | `03_Drawing_and_Annotation.ipynb` |
| **04** | Image Transformations: Translation, Rotation, Resizing, Flipping, Cropping | `04_Image_Transformations.ipynb` |
| **05** | Image Processing: Arithmetic, Bitwise Operations, Masking, Splitting & Merging Channels, Color Spaces | `05_Image_Processing.ipynb` |
| **06** | Histograms: Grayscale & Color, Histogram Equalization, Histograms with Masks | `06_Histograms.ipynb` |
| **07** | Smoothing & Blurring: Kernels, Convolution, Averaging, Gaussian, Median, & Bilateral Filtering | `07_Smoothing_and_Blurring.ipynb` |
| **08** | Morphological Transformations: Erosion, Dilation, Opening, Closing, Gradient | `08_Morphological_Transforms.ipynb` |
| **09** | Thresholding: Simple (Binary, Inverse), Otsu's Thresholding | `09_Thresholding.ipynb` |
| **10** | Edge & Contour Detection: Sobel & Scharr Operators, Canny Edge Detection, Finding & Drawing Contours | `10_Edge_and_Contour_Detection.ipynb` |

## 📖 Reference Material

The course and notebooks are based on concepts from the following book:
* **Programming Computer Vision with Python:** Tools and algorithms for analyzing images by Jan Erik Solem
