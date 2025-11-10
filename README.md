# Computer Vision Assessment Task: Black Gun Detection
the inference video can be downloaded here https://drive.google.com/drive/folders/1m0DQjhCUc1-6lgnj8Py7H93PPlSaS7WD?usp=sharing
## How to run the notebook
      1. clone this repos and install the requirement.txt
      2. download the dataset here https://drive.google.com/drive/folders/1m0DQjhCUc1-6lgnj8Py7H93PPlSaS7WD?usp=sharing 
      3. run the notebook for training and inference

## Training Results using Synthetic Data (SD)
![Synthetic Data Results](https://raw.githubusercontent.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/main/runs/detect/train/results.png)
- Loss curves (train and val):
      They decrease overall, but fluctuate noticeably, especially in validation losses (val/dfl_loss and val/box_loss).
      This fluctuation suggests synthetic data introduces less consistent patterns, possibly due to unrealistic variations or lack of diversity.
- Precision & Recall:
      The early spike and slight oscillations indicate the model instability.

## Training Results using Real Data
![Real Data Results](https://raw.githubusercontent.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/main/runs/detect/train4/results.png)
- Loss curves (train and val):
      Much smoother and more stable than synthetic data.
      Indicates consistent learning and better generalization.
- Precision & Recall:
      Both stabilize early and remain flat, showing strong reliability.


  # Inference Synthetic Data Model and Real Data Model
  
<p align="center">
  <b>Synthetic Data inference:</b><br>
   <img src="https://raw.githubusercontent.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/refs/heads/main/runs/SD%20inf1.png">
  < <img src="https://raw.githubusercontent.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/refs/heads/main/runs/SD%20inf2.png">
  https://raw.githubusercontent.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/refs/heads/main/runs/SD%20inf3.png
</p>




