# NeuroVision - Brain Tumor Segmentation Project

## Overview

This project introduces an advanced approach to brain tumor segmentation using a 3D U-Net model on MRI data. The primary goal is to enhance accuracy and efficiency in brain tumor detection and segmentation for improved medical diagnostics and treatment planning.

## Key Features

- **3D U-Net Model:** Utilizes a specialized Convolutional Neural Network (CNN) for processing MRI slices and constructing detailed 3D tumor representations.

- **Improved Segmentation:** Addresses limitations of 2D imaging by capturing spatial hierarchies and complex patterns in volumetric data, resulting in enhanced segmentation accuracy.

- **Validation:** Evaluated on the BRATS 2020 dataset, confirming superior segmentation accuracy compared to conventional methods.

## Project Objectives

1. **Enhance Visualization:** Provide medical professionals with a detailed 3D model for improved visualization and analysis of brain tumor anatomy.

2. **User-Friendly Interface:** Develop an intuitive graphical user interface (GUI) to facilitate interaction and manipulation of 3D models.

3. **Algorithm Optimization:** Fine-tune the 3D U-Net algorithm for enhanced efficiency, considering computational resource limitations.

## Project Scope

Focused on Neurosciences, particularly neuro-oncology, to advance healthcare in nervous system-related areas such as the brain and spinal cord.

## Limitations

1. **Tumor Heterogeneity:** Challenges in accurately segmenting heterogeneous tumors.
2. **Complex Features:** Addressing complexities like necrotic cores and vasculature.
3. **Ethical Considerations:** Ensuring patient privacy and ethical data usage.
4. **Clinical Validation:** Challenges in validating 3D tumor representations against ground truth.
5. **Expertise Requirements:** Medical professionals may need specialized training.

## Expected Output

Introducing a state-of-the-art interface for processing 3D MRI slices, deploying a sophisticated 3D U-Net model for accurate and detailed brain tumor representations.

## Technical Feasibility

- **Colab Pro Plus:** Utilizing cloud-based Colab Pro Plus for model development, ensuring scalability and accessibility.
- **Spyder:** GUI development using Spyder for a user-friendly interface and efficient testing.
- **Integration of 3D U-Net:** Seamless integration with the GUI for effective interaction and analysis.
- **Computational Challenges:** Addressed through Colab Pro Plus and Spyder to ensure smooth workflow and high performance.

## Dataset and Preprocessing

Utilizing the BRATS 2020 dataset, comprising various MRI scans with annotations for tumor regions. Data preprocessing involves stacking modalities, depth padding, and storage in NPY format for efficient processing.

## Methodology

- **Data Division:** Training the 3D U-Net model in chunks due to computational constraints, ensuring exposure to diverse data.
- **Session Management:** Clearing sessions post-training chunks to avoid memory overflow and maintain system performance.

## Targeted Users

Primarily designed for medical professionals and staff, particularly radiologists, involved in diagnosing and treating patients.

## Functional Requirements

### User:
1. Access the system.
2. Image Import.
3. Interactive 3D Visualization.
4. Tumor Segmentation and Highlighting.
5. Exporting the result in .STL format.
6. Training and Support.

### Administrator:
1. System Monitoring and Maintenance.
2. Security and Privacy Management.
3. System Integration.

## Interviews

Collaborative discussions with a supervising doctor and postgraduate students enriched the requirements gathering process, providing insights into practical implementation and challenges in brain tumor analysis.

## Conclusion

This project aims to revolutionize brain tumor segmentation by combining advanced algorithms, user-friendly interfaces, and comprehensive datasets, ultimately improving diagnostic accuracy in neuro-oncology.
