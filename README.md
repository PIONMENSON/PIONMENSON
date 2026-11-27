# Hyojun Yun

I study robot manipulation and robot learning at Sungkyunkwan University. My interests include visual and tactile perception, vision-language-action (VLA) models, and efficient training and inference with neural processing units (NPUs).

[Website](https://pionmenson.github.io/) · [Email](mailto:yhj0971@gmail.com) · [Research papers](https://textbook-hub.vercel.app/#research) · [Learning notes](https://textbook-hub.vercel.app/)

## Selected Research

### Tactile Encoders for Vision-Language-Action Models in Occluded Manipulation

Master's thesis research · RISE Lab, Sungkyunkwan University

SmolVLA-Touch uses fingertip tactile signals and joint history to estimate object pose and insertion state. A fast tactile path corrects action chunks as contact changes during insertion, even when the work area is hidden from the cameras.

[Research overview](https://pionmenson.github.io/#masters-research) · [Slides (PDF, English)](https://pionmenson.github.io/papers/tactile-vla-presentation.pdf?v=20261127-desktop)

### NPU Offloading of a Frozen Visual Encoder for Robot Policy Training

An asynchronous training pipeline that runs a frozen visual encoder on an NPU while training the action module on a GPU. The arXiv preprint reports lower accelerator-board energy per sample, with longer training time and lower policy success rates than GPU-only training.

[Project page](https://textbook-hub.vercel.app/npu-offload/) · [Paper (PDF)](https://textbook-hub.vercel.app/npu-offload/paper.pdf)

## Learning Notes

My study notes and interactive exercises on robotics, control, VLA models, and programming. The explanations are primarily in Korean.

<a href="https://textbook-hub.vercel.app/">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PIONMENSON/PIONMENSON/main/assets/notes-mobile-dark.svg?v=20261126-en">
    <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/PIONMENSON/PIONMENSON/main/assets/notes-mobile-light.svg?v=20261126-en">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PIONMENSON/PIONMENSON/main/assets/notes-dark.svg?v=20261126-en">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PIONMENSON/PIONMENSON/main/assets/notes-light.svg?v=20261126-en">
    <img src="https://raw.githubusercontent.com/PIONMENSON/PIONMENSON/main/assets/notes-light.svg?v=20261126-en" width="760" alt="Open learning notes on robotics, VLA, and programming">
  </picture>
</a>

[Robotics & Control](https://textbook-hub.vercel.app/?topic=robot) · [VLA](https://textbook-hub.vercel.app/?topic=vla) · [Programming](https://textbook-hub.vercel.app/?topic=cs)
