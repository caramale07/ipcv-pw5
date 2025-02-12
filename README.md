# PW5 - Image Blending with OpenCV and Matplotlib

[GitHub Repository](https://github.com/yourusername/yourrepository)

This project demonstrates a simple image processing and computer vision task where two images are blended together. Specifically, I blended a primary image (`dog_backpack.png`) with a watermark to create a watermarked version of the original image. The final output is saved in the `images` directory.

## Libraries Used

- **OpenCV (cv2):** Used for reading, processing, and blending images.
- **Matplotlib:** Utilized for displaying images, especially useful in notebook environments or when GUI support is not available.

## Project Overview

- **Input Image:**  
  - `dog_backpack.png` – The main image on which the watermark will be applied.
- **Watermark:**  
  - A watermark image is blended with the main image.
- **Process:**  
  1. Load the main image and the watermark.
  2. Blend the watermark with the main image using OpenCV functions.
  3. Save the resulting image in the `images` directory.
- **Output:**  
  - The blended image (with the watermark) is stored in the `images` directory.

## How to Run

1. **Install Dependencies:**  
   Ensure that you have Python installed, then install the required libraries:
   ```bash
   pip install opencv-python matplotlib
