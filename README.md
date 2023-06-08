## Skin Cancer Detection using YOLO v5 and YOLO v8

### Introduction
This project aims to develop a skin cancer detection system using the YOLO (You Only Look Once) object detection algorithm. The system utilizes two versions of YOLO, namely YOLO v5 and YOLO v8, to detect and classify different types of skin lesions associated with skin cancer. The models are trained on the HAM10000 dataset, which contains labeled skin images, and provide accurate predictions for the presence of skin cancer.

### Prerequisites
To run the skin cancer detection system, the following prerequisites are required:
- Python 3.x
- Jupyter Notebook
- PyTorch
- OpenCV
- CUDA (for GPU acceleration, optional but recommended)

### Getting Started
1. Clone the repository to your local machine.
2. Make sure you have the HAM10000 dataset available and stored in the folder `/content/HAM10000/`.
3. Ensure that you have the necessary IPython Notebook (`.ipynb`) files for both YOLO v5 and YOLO v8 implementations.
4. Create two separate folders named `yolov5` and `yolov8`.
5. Place the respective IPython Notebook files into their corresponding folders (`yolov5` for YOLO v5 and `yolov8` for YOLO v8).

### Running the Detection
1. Launch Jupyter Notebook.
2. Open the IPython Notebook file for YOLO v5.
3. Ensure that the necessary dependencies and libraries are installed by running the required installation commands within the notebook.
4. Execute the notebook cells sequentially to perform skin cancer detection using YOLO v5.
5. The output results will be saved in the `results_yolov5` folder.

6. Open the IPython Notebook file for YOLO v8.
7. Install any required dependencies and libraries if needed.
8. Execute the notebook cells in order to perform skin cancer detection using YOLO v8.
9. The output results will be saved in the `results_yolov8` folder.

**Note**: Make sure the HAM10000 dataset is properly organized within the `/content/HAM10000/` folder, containing the necessary subfolders and image files. The IPython Notebooks should handle the dataset loading and preprocessing based on the provided folder structure.

By following these steps, you will be able to run the skin cancer detection system using YOLO v5 and YOLO v8 implementations and observe the results in the respective result folders.
