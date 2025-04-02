Swin UNetR architecture has a transformer Encoder and a CNN based decoder. I strengthened the skip connections and made them fused over multiple levels in order to increase 3D segmentation performance(Dice score).
Pre-training involved MAE(Masked AutoEncoder) inspired reconstruction training(50% of the 3D input randomly blacked, to be reconstructed)

This was my Master's thesis project in 2023.
