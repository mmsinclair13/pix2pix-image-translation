# Pix2Pix Image-to-Image Translation — TensorFlow

Replicated TensorFlow’s pix2pix tutorial to generate building facade images from paired label maps using the CMP Facades dataset. Implemented image preprocessing and augmentation, a U-Net generator with skip connections, and a PatchGAN discriminator. Built a custom training loop combining adversarial and L1 reconstruction losses, with TensorBoard logging, checkpoint support, and visual comparisons of generated images against ground truth.

## Current status

An initial 100-step training run is recorded in the uploaded notebook. As of October 6, 2026, a separate 40,000-step training run is underway; its results and checkpoints are not included in this snapshot.

## Notebook

[Untitled0 (1).ipynb](Untitled0%20%281%29.ipynb) is uploaded unchanged, including its saved outputs.

## Reference

Based on the [TensorFlow Pix2Pix Tutorial](https://www.tensorflow.org/tutorials/generative/pix2pix), implementing the approach described in [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004) by Isola et al.
