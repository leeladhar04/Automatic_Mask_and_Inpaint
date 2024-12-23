# Automatic Masking and Inpainting with Stable Diffusion

This repository contains a Python notebook that demonstrates automatic image masking using the **Segment Anything Model (SAM) and You Only Look Once (YOLO)** and inpainting using the **Stable Diffusion Inpainting pipeline**. The project showcases how cutting-edge AI models can be used to mask objects in an image automatically and fill in the masked regions using context-driven prompts.

---

## Overview

### Objectives:
- Automatically mask objects in an image using SAM and YOLOv8.
- Perform inpainting to replace masked regions with contextually accurate content using Stable Diffusion.
- Provide a user-friendly pipeline for both technical and non-technical users.

---

## Workflow

1. **Input Image**: The user provides an image that requires masking and inpainting.
2. **Automatic Masking**: 
   - YOLOv8 detects objects in the image.
   - SAM generates masks for the detected objects.
3. **Image Preview**:
   - The notebook displays the original and masked images side by side.
4. **Inpainting**:
   - Using the Stable Diffusion Inpainting pipeline, the masked regions are filled based on a user-provided prompt.

![Workflow Diagram](Images/workflow.jpg)

---

## Examples

### Input Image:
![Input Image](Images/img2.png)

### Masked Image:
![Masked Image](Images/mask2.png)

### Inpainted Image:
![Inpainted Image](Images/gen6.png)

---

## Getting Started

Just run the following notebook :- https://colab.research.google.com/drive/1-VOQ2ziByv3WL6SSOPopLn2OLEUdsc5i?usp=sharing

**Results**
The following example showcases the pipeline:
### Input Image:
![Input Image](Images/img3.png)

### Masked Image:
![Masked Image](Images/mask3.png)

### Inpainted Image:
![Inpainted Image with prompt (happy brown bear)](Images/gen4.png)


### Input Image:
![Input Image](Images/img4.png)

### Masked Image:
![Masked Image](Images/mask4.png)

### Inpainted Image:
![Inpainted Image with prompt (newspaper)](Images/gen1.png)



