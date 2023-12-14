# SOP Violation Detection with Multi-Camera System

This project, implemented in six distinct phases, focuses on developing a COVID-19 SOP violation detection system utilizing a multi-camera setup. Each phase contributes to the overall functionality and effectiveness of the system.

## Phases:

### 1. Live Streaming Setup
   - The initial phase establishes live streaming from a triple camera setup, forming the foundation for subsequent phases.

### 2. Mask Detection
   - Leveraging the YOLOv5 model, the second phase addresses mask detection, ensuring accurate identification using a trained model.

### 3. Orthogonal Top View Projection
   - In the third phase, the system achieves orthogonal top-view projection, enhancing perspective and aiding in comprehensive analysis.

### 4. Dot Projection in Top View
   - Building upon the third phase, the fourth phase replaces bounding boxes with dots in the generated top view for both "mask" and "no_mask" classifications.

### 5. SOP Violation Detection
   - The fifth phase focuses on detecting SOP violations, employing the insights gained from previous phases to enhance accuracy.

### 6. Heatmap Generation
   - The final phase generates three distinct heatmaps:
     - Static heatmap for all detections.
     - Animated heatmap for all detections.
     - Heatmap specifically highlighting SOP violations.


The idea was to enhance public safety with effective surveillance and violation identification. 🦠🚫
