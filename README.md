# Object Detection using YOLOv8 on VisDrone Dataset

This project implements object detection using **YOLOv8** on the **VisDrone** dataset, which contains aerial/drone images with many small objects.

## Project Overview

- **Goal**: Improve object detection performance on small objects using YOLOv8
- **Dataset**: VisDrone (subset of 1500 training + 300 validation images)
- **Models Used**:
  - YOLOv8n → Baseline
  - YOLOv8s → Improved Model
- **Framework**: Ultralytics YOLOv8
- **Platform**: Google Colab

## Dataset Details

| Item              | Details                          |
|-------------------|----------------------------------|
| Dataset           | VisDrone                         |
| Total Images Used | 1800 (1500 train + 300 valid)    |
| Classes           | 10 (pedestrian, people, bicycle, car, van, truck, tricycle, awning-tricycle, bus, motor) |
| Image Size        | 640 × 640                        |

## Results

| Model       | mAP50  | mAP50-95 |
|-------------|--------|----------|
| YOLOv8n     | 0.322  | 0.114    |
| **YOLOv8s** | **0.410** | **0.157** |

**Improvement**: +0.088 mAP50 by using YOLOv8s over YOLOv8n

## Project Structure
