# Image Captioning Using BLIP: A Pre-Trained Vision-Language Model

This project demonstrates the use of BLIP (Bootstrapped Language-Image Pre-training) for generating captions for images using a pre-trained model from Hugging Face's Transformers library. The model is fine-tuned to describe various images effectively and has been tested using publicly available datasets.

---

## Dataset Used for Testing

The project uses the **Aquarium > raw-1024** dataset, provided by [Roboflow](https://roboflow.com), for testing the captioning functionality. This dataset contains 638 images of aquatic life from two aquariums in the United States:  
- **Henry Doorly Zoo in Omaha** (October 16, 2020)  
- **National Aquarium in Baltimore** (November 14, 2020)  

The images are annotated for object detection and include labeled classes such as **fish, jellyfish, penguins, sharks, puffins, stingrays, and starfish.**  

The dataset is licensed under **CC BY 4.0**, allowing personal, commercial, and academic usage with appropriate attribution. Learn more [here](https://public.roboflow.ai/object-detection/aquarium).

---

## Requirements

- Python 3.7+
- Install the dependencies:
  ```bash
  pip install transformers opencv-python torch
