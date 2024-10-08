# YOLOv5 Person Tracking with Unique ID Assignment

This repository contains a YOLOv5-based person tracking system, where each individual detected in the video frames is assigned a unique ID. The system enables real-time tracking of individuals across multiple frames.

## Features:
- **Person detection** in real-time using YOLOv5.
- **Unique ID assignment** for each detected individual.
- **Person tracking** across video frames using the assigned IDs.

## Table of Contents:
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Model Details](#model-details)
4. [Pre-processing](#pre-processing)
5. [Results](#results)
6. [How to Run](#how-to-run)

## Project Overview:
This project uses YOLOv5 to detect and track individuals in video frames. A unique ID is assigned to each detected person to ensure they are tracked consistently throughout the video.

## Dataset:
The dataset consists of video recordings of multiple individuals, where bounding boxes are generated for each person and a unique ID is assigned for tracking. Due to privacy concerns, the dataset is not available to the public.

## Model Details:
YOLOv5 is utilized for detecting individuals in real-time, and unique tracking IDs are assigned to maintain person identification across video frames.

## Pre-processing:
Prior to using the YOLOv5 model, the video frames are resized, and data augmentation is applied to enhance the model's performance and accuracy.

## Results:
The system was able to successfully track individuals by assigning unique IDs. Below are two sets of videos showing the tracking results:

- **Before the operation:**
   - [Video 1]

https://github.com/user-attachments/assets/de7d9a21-b85d-443d-8cbd-d8dfc79b2d47


   - [Video 2]

https://github.com/user-attachments/assets/62259b6a-1b50-402a-95bd-9ff36806e607




- **After the operation:**
   - [Video 1]


https://github.com/user-attachments/assets/c466ff83-864d-4626-be5d-63128e829067

   - [Video 2]

https://github.com/user-attachments/assets/201b635b-b2fe-4011-9a1a-9613104c475e






## How to Run:
1. Clone the repository:
   ```bash
   git clone </CodeNinjaSarthak/YOLOv5-Person-Tracking-with-Unique-ID-Assignment/>
   cd <YOLOv5-Person-Tracking-with-Unique-ID-Assignment>
