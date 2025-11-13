# Computer Vision (PG-DUASP) - Lab Assignments

[cite_start]This repository contains the practical lab assignments and code examples for the **Computer Vision (PG-DUASP)** course[cite: 2]. The code is written in Python using Jupyter Notebooks (`.ipynb`) and primarily utilizes the OpenCV and Matplotlib libraries.

[cite_start]The main objective of this course and repository is to introduce students to the fundamentals of Computer Vision[cite: 4].

##  Prerequisites

[cite_start]A good working knowledge of the following is recommended[cite: 5]:
* [cite_start]Python Programming [cite: 5]
* [cite_start]Mathematics (Linear Algebra) [cite: 5]

## 🛠️ Setup and Installation

To run the notebooks in this repository, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Install the required libraries:**
    It is highly recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
    *If you do not have a `requirements.txt` file, you can install the main packages manually:*
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
| **01** | [cite_start]Introduction to CV, Loading, Displaying & Saving Images, Grayscale vs. Color, BGR vs. RGB, `cmap` [cite: 17-25] | `01_Image_Basics.ipynb` |
| **02** | [cite_start]Image & Video Basics, Pixels, Coordinate Systems, Pixel Manipulation, Video Capturing & Playing [cite: 29-34] | `02_Video_Basics.ipynb` |
| **03** | [cite_start]Drawing Functions (Lines, Rectangles, Circles), Annotating Images, Mouse as a Paintbrush [cite: 40-44] | `03_Drawing_and_Annotation.ipynb` |
| **04** | [cite_start]Image Transformations: Translation, Rotation, Resizing, Flipping, Cropping [cite: 48-53] | `04_Image_Transformations.ipynb` |
| **05** | [cite_start]Image Processing: Arithmetic, Bitwise Operations, Masking, Splitting & Merging Channels, Color Spaces [cite: 57-63] | `05_Image_Processing.ipynb` |
| **06** | [cite_start]Histograms: Grayscale & Color, Histogram Equalization, Histograms with Masks [cite: 67-73, 76] | `06_Histograms.ipynb` |
| **07** | [cite_start]Smoothing & Blurring: Kernels, Convolution, Averaging, Gaussian, Median, & Bilateral Filtering [cite: 80-86] | `07_Smoothing_and_Blurring.ipynb` |
| **08** | [cite_start]Morphological Transformations: Erosion, Dilation, Opening, Closing, Gradient [cite: 89, 91] | `08_Morphological_Transforms.ipynb` |
| **09** | [cite_start]Thresholding: Simple (Binary, Inverse), Otsu's Thresholding [cite: 94-97] | `09_Thresholding.ipynb` |
| **10** | [cite_start]Edge & Contour Detection: Sobel & Scharr Operators, Canny Edge Detection, Finding & Drawing Contours [cite: 101-105] | `10_Edge_and_Contour_Detection.ipynb` |

## 📖 Reference Material

The course and notebooks are based on concepts from the following book:
* [cite_start]**Programming Computer Vision with Python:** Tools and algorithms for analyzing images by Jan Erik Solem [cite: 10]
