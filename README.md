# Final Submission

This repository contains the final submission for our projects, including both reports and source code implementations. 

## Projects

### 1. Direct Sparse Odometry (DSO) and DM-VIO
- **Objective:** Comparative analysis of pose estimation techniques.
- **Highlights:**
  - Implementation of DSO and DM-VIO for pose estimation.
  - Benchmarking performance on real-world datasets.

### 2. Semi-Global Block Matching (SGBM) and 3D Scene Reconstruction
- **Objective:** Compute stereo image disparity and reconstruct 3D scenes.
- **Highlights:**
  - Implementation of SGBM from scratch.
  - Transformation of disparity maps into 3D point clouds using stereo camera geometry.

---

## Datasets

### 1. SGBM
- For the SGBM project, we used the KITTI stereo dataset.  
  Download the dataset from the official KITTI website:  
  [KITTI Stereo Dataset](https://www.cvlibs.net/datasets/kitti/eval_stereo_flow.php?benchmark=stereo)

### 2. DSO and DM-VIO
- For DSO and DM-VIO, we used multiple sequences from the TUM Visual-Inertial Dataset.  
  Download the dataset here:  
  [TUM Visual-Inertial Dataset](https://cvg.cit.tum.de/data/datasets/visual-inertial-dataset)

---

## Setup and Instructions

### 1. Direct Sparse Odometry (DSO)
- Refer to the `README.md` file in the `DSO` folder for detailed setup and build instructions.
- Follow the steps to configure the DSO environment and run the sequences.

### 2. Semi-Global Block Matching (SGBM)
- The SGBM project uses only basic Python libraries and does not require a complex setup.
- **Install the required dependencies**:
    ```bash
    pip install numpy matplotlib pandas opencv-python
    ```
- **Run the code**:
    ```bash
    cd src
    python check.py # This is the main file
    ```
- Ensure the KITTI dataset is placed in the specified directory before execution.

---

## Results and Plots

- All plots and figures included in the report are stored in the repository.  
- Instructions to regenerate these plots are provided in the respective directories.

---

## Contributors

1. Aryan Garg  
2. Pratyush Jena  
