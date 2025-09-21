
# YOLOv8 Tumor Detection - Automated Report

## 1️⃣ Project Overview
This report documents the training of a **YOLOv8 model for tumor detection** using custom medical imaging datasets with YOLO-formatted bounding box labels.

## 2️⃣ Training Summary
- **Total Epochs Trained:** 50
- **Image Size:** 640x640
- **Batch Size:** 8
- **Model:** YOLOv8n.pt

## 3️⃣ Validation Metrics Across Epochs
![Validation Metrics](report_plots/validation_metrics.png)

## 4️⃣ Training Loss Across Epochs
![Training Loss](report_plots/training_loss.png)

## 5️⃣ Key Observations
- The mAP@0.5 and mAP@0.5:0.95 curves provide insights into model generalization on validation data.
- Loss curves help track overfitting or underfitting.
- Precision, Recall, and F1-score trends confirm detection consistency.

## 6️⃣ Next Steps
- Evaluate the best model checkpoint using detailed test data.
- Run inference on unseen tumor scan images.
- If needed, fine-tune using advanced augmentation or a larger YOLOv8 model variant.
- Deploy to ONNX/TensorRT for real-time hospital or clinical edge deployment.

---

_This report was auto-generated to maintain clean documentation during experimentation._
