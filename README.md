# Computer Vision Assessment Task: Black Gun Detection
## how to run the notebook

## Training Results using Synthetic Data (SD)
https://github.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/blob/main/runs/detect/train/results.png
- Loss curves (train and val):
      They decrease overall, but fluctuate noticeably, especially in validation losses (val/dfl_loss and val/box_loss).
      This fluctuation suggests synthetic data introduces less consistent patterns, possibly due to unrealistic variations or lack of diversity.
- Precision & Recall:
      Both reach high values quickly, but the early spike and slight oscillations indicate the model adapts fast but with instability.

## Training Results using Real Data
https://github.com/hafidzali04/Assestment_Bluesilo_Gun_Detection/blob/main/runs/detect/train4/results.png
- Loss curves (train and val):
      Much smoother and more stable than synthetic data.
      Indicates consistent learning and better generalization.
- Precision & Recall:
      Both stabilize early and remain flat, showing strong reliability.

