# CLCXray Object Detection using Computer Vision

Welcome to the **Smart Screening: Identifying Restricted Items in
 CLCXray Images with YOLO Models** project!  

This repository contains our work on applying advanced computer vision models (YOLO variants) for detecting abnormalities in chest X-ray images.

---

## 📄 Detailed Report

For the full project report, methodology, metrics, and detailed results, check out the PDF:

👉 [**View the Project Report**](https://github.com/Sarayu30/clcxray_object_detection_computervision/blob/main/Project_Report.pdf)

---

## 📊 Summary of Results

| S.No | Model              | Precision | Recall | mAP@50 | mAP@50–95 | F1-Score |
|------|---------------------|-----------|--------|--------|-----------|----------|
| 1    | YOLOv9m             | 0.805     | 0.664  | 0.711  | 0.612     | 0.728    |
| 2    | YOLOv11            | 0.777     | 0.627  | 0.665  | 0.555     | 0.694    |
| 3    | YOLOv12            | 0.856     | 0.648  | 0.703  | 0.600     | 0.738    |
| 4    | YOLOv5s           | 0.858     | 0.643  | 0.689  | 0.574     | 0.735    |
| 5    | YOLOv8s           | 0.793     | 0.666  | 0.692  | 0.594     | 0.724    |
| 6    | YOLOv10n          | 0.819     | 0.648  | 0.690  | 0.584     | 0.723    |
| 7    | YOLOv9m (ResBlock) | 0.816     | 0.609  | 0.665  | 0.547     | 0.667    |
| 8    | YOLOv9m (CBAM)    | 0.781     | 0.621  | 0.659  | 0.548     | 0.672    |

---

## 🚀 Models Used

We evaluated several YOLO architectures, incorporating enhancements like ResBlock and CBAM attention modules, to improve detection performance.

Metrics reported:
✅ **Precision**  
✅ **Recall**  
✅ **mAP@50**  
✅ **mAP@50–95**  
✅ **F1-Score**

---

If you found this project helpful, please ⭐ **star** the repo!

