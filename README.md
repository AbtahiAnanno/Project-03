# Project-03
# Face Inpainting with Attention U-Net GAN

## Problem
Restore corrupted/masked face images using deep learning.

## Architecture
•⁠  ⁠*Generator*: Attention U-Net (4 encoder blocks, dilated bridge, 4 decoder blocks with Spatial Attention gates)
•⁠  ⁠*Discriminator*: PatchGAN critic
•⁠  ⁠*Loss*: L1 + VGG Perceptual + Style (Gram) + Adversarial

## Dataset
CelebA – 12,000 images split 80/10/10 (train/val/test)

## Metrics Tracked
PSNR, SSIM, L1 Loss, Perceptual Loss, Masked MAE
