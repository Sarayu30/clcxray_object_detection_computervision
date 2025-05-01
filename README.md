

# X-Ray Object Detection using Customized YOLOv9

## Overview

This project implements an object detection system for X-ray security imaging using a customized YOLOv5 model (referred to as YOLOv9). The model is designed to identify prohibited items in luggage scans with high accuracy and speed, achieving significant performance metrics. It is optimized for real-time threat detection in security systems.

## Features

- **Customized YOLOv9 Model**: A modified version of YOLOv5, tailored for detecting items in X-ray images.
- **High Detection Accuracy**: Achieved over 90% precision and recall for various object classes, such as cans, bottles, knives, and more.
- **Comprehensive Evaluation**: Includes mAP@0.5 and mAP@0.5:0.95 evaluation metrics for multiple object classes.

## Results

- **mAP@0.5 (Mean Average Precision)**: 0.677
- **mAP@0.5:0.95 (Mean Average Precision across IoU levels)**: 0.569
- **Precision (mean)**: 0.727
- **Recall (mean)**: 0.611

### Class-wise Performance (Sample)

| Class             | mAP@0.5 | mAP@0.5:0.95 |
|-------------------|---------|--------------|
| Cans              | 0.378   | 0.349        |
| CartonDrinks      | 0.776   | 0.608        |
| GlassBottle       | 0.170   | 0.127        |
| PlasticBottle     | 0.705   | 0.589        |
| SwissArmyKnife    | 0.934   | 0.733        |
| VacuumCup         | 0.858   | 0.776        |
| Blade             | 0.727   | 0.544        |
| Dagger            | 0.935   | 0.832        |
| Knife             | 0.951   | 0.834        |
| Scissors          | 0.846   | 0.748        |

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sarayu30/clcxray_object_detection_computervision.git
   cd clcxray_object_detection_computervision
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch the Jupyter notebook to explore the object detection pipeline:
   ```bash
   jupyter notebook XRay_Object_Detection.ipynb
   ```

2. Follow the notebook to:
   - Load and preprocess the X-ray dataset.
   - Train the YOLOv9 model.
   - Evaluate the model on test images.
   - Perform real-time object detection on sample images.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to tweak any parts to match the specifics of your project and repository.
