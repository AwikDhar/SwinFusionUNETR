Swin UNetR architecture has a transformer Encoder and a CNN based decoder. I strengthened the skip connections and made them fused over multiple levels in order to increase 3D segmentation performance(Dice score).
Pre-training involved MAE(Masked AutoEncoder) inspired reconstruction training(50% of the 3D input randomly blacked, to be reconstructed)

This was my Master's thesis project in 2023.

<h3>Model Architeture</h3>
Here's a model diagram of Swin Fusion UNETR with 4 stages for the sake of simplicity(actual model has 5 stages).

![swin fusion](https://github.com/user-attachments/assets/c56ef3fc-011b-46c2-b82f-d735cf4abfa2)

Only the skip connection fusion over the last stage is explicitly drawn, with the fusion for other stages implied via the connections.

<h3>**Results:**</h3>

![image](https://github.com/user-attachments/assets/cd4ff77a-2a45-48f1-ade0-220af37ae52f)

For more details, please refer to the attached report.
