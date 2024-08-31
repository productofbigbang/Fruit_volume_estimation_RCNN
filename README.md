

## Image Segmentation Project

This project focuses on image segmentation using a Mask R-CNN model with a ResNet-50 backbone. It's designed to work with a dataset of fruit images, for fruit detection or analysis.

### Setup

The project uses Python 3 and requires the following libraries:

- OpenCV (cv2)
- NumPy
- PyTorch
- torchvision
- Pillow (PIL)
- pandas

To install the required libraries, run:

```bash
pip install opencv-python numpy torch torchvision pillow pandas
```

### Dataset

The dataset is structured as follows:

- Root directory: `/kaggle/input/isb-data/`
- CSV file: `Dataset_clean/dataset.csv`
- Image directory: `Dataset_clean/apple/2/`

The dataset contains numerous JPEG images of apples, along with a CSV file that likely contains metadata or annotations for the images.

### Code Structure

The code is divided into two main parts:

1. **Library Imports**: The necessary libraries are imported, including CV2, NumPy, PyTorch, and others.

2. **Data Exploration**: A script to explore the dataset structure, listing all files in the input directory.

### Usage

To use this project:

1. Ensure all required libraries are installed.
2. Place the dataset in the appropriate directory (`/kaggle/input/isb-data/`).
3. Run the data exploration script to verify the dataset structure.
4. Implement the image segmentation model using the imported Mask R-CNN from torchvision.

### Next Steps

The current code sets up the environment and explores the dataset. To complete the project:

1. Load and preprocess the images.
2. Set up the Mask R-CNN model.
3. Train the model on the apple dataset.
4. Implement inference to segment new apple images.
5. Evaluate the model's performance.

### Notes

- The project is set up to run in a Kaggle environment with GPU acceleration.
