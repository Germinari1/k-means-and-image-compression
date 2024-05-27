# k-means-and-image-compression
This project implements the K-Means clustering algorithm and applies it to image compression. The core idea is to reduce the number of colors in an image to a smaller set of representative colors, thereby compressing the image data while retaining its essential visual characteristics.
## Project Overview

The project covers the following aspects:

1. **Implementing K-Means Algorithm**:
  - Finding closest centroids for data points
  - Computing centroid means based on cluster assignments

2. **Running K-Means on a Sample Dataset**:
  - Visualizing the convergence of centroids and cluster assignments

3. **Random Initialization of Centroids**:
  - Understanding the impact of different initial centroid positions

4. **Image Compression with K-Means**:
  - Loading and preprocessing an image
  - Running K-Means on image pixels
  - Compressing the image by replacing pixels with closest centroid colors

## Dependencies

The project requires the following Python libraries:

- NumPy
- Matplotlib
- utils (provided in the project)

You can install the required dependencies using the following command:
```txt
pip install numpy matplotlib
```
