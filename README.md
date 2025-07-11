# Football-Automated-VAR-Model
This project investigates the automatic classification of foul events in football match footage using deep learning video models, trained on the specialized Soccernet-MVFouls dataset. The system aims to support VAR referees or leagues without VAR capabilities by distinguishing between no fouls, regular fouls, yellow card fouls, and red card fouls from single-view video clips.

Core Highlights:
- Dataset: 3,901 referee-annotated foul events from top European matches, with 10 detailed labels per event.
- Focused on single-view classification, using clips with only one perspective (to increase sample size and realism).

Models Used:
- Pretrained models from PyTorch: r3d_18, mc3_18, r2plus1d_18 (based on ResNet backbones).
- Transfer learning from Kinetics-400 video dataset.

Why It Matters:
- Tackles the real-world challenge of referee decision inconsistency with scalable AI.
- Valuable for leagues without VAR, as an automated referee support tool.
- Demonstrates model adaptability to noisy, imbalanced, and multiclass video data in sports.

Visualization:
These clip were correctly classified to be a foul with no card

https://github.com/user-attachments/assets/45cb8776-3b6c-4334-a74a-c5f04c6dcc23

https://github.com/user-attachments/assets/9bda303b-cc49-4ab7-94d4-315f1581cf13

