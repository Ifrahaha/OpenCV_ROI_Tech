# **Image Segmentation and Clustering Techniques**

This repository implements various image segmentation and clustering techniques using **OpenCV**, **Keras**, and **Skimage**. These techniques are widely used in computer vision tasks, such as image segmentation, clustering, and region of interest (ROI) detection.

## **Contents**

Here is a brief description of each tech:

1. **`Watershed_Algorithm.ipynb`**  
   - Implementation of the **Watershed Algorithm** to segment images by treating pixel intensity as topographic information. This technique is useful for separating overlapping objects in an image.

2. **`GradCAM_Implementation.ipynb`**  
   - Demonstrates **Grad-CAM** (Gradient-weighted Class Activation Mapping), a visualization technique that highlights important regions in an image used by deep learning models during classification.

3. **`KMeans_Clustering.ipynb`**  
   - Implementation of **K-Means Clustering** to group pixels based on their color intensity and segment the image into different clusters. This is an unsupervised learning method used for color-based segmentation.

4. **`Thresholding_Techniques.ipynb`**  
   - Applies various **thresholding techniques** to distinguish objects from the background in grayscale images. The notebook includes Otsu's method, global thresholding, and adaptive thresholding techniques.

5. **`HSV_Based_Segmentation.ipynb`**  
   - Segments an image using the **HSV (Hue, Saturation, Value) color space**. This technique is particularly useful for color-based segmentation tasks, separating objects in an image based on hue and saturation levels.


## **Dependencies**

The notebooks in this repository require the following dependencies:

- Python 3.x
- OpenCV
- Numpy
- Matplotlib
- Scikit-Image
- TensorFlow (for Grad-CAM visualization)

You can install the required libraries using the following pip command:

```bash
pip install opencv-python numpy matplotlib scikit-image tensorflow
```

## **How to Use**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ifrahaha/OpenCV_ROI_Tech.git
   cd OpenCV_ROI_Tech
   ```

