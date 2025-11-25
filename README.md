# STAG 25 - 3D Reconstruction Lab

This repo contains a notebook (to run on Colab) and the required data/model assets.
This is a demo for the pipeline introduced in:
[*Model-based Metric 3D Shape and Motion Reconstruction of Wild Bottlenose Dolphins in Drone-Shot Videos*](https://arxiv.org/abs/2504.15782) by 
Daniele Baieri, Riccardo Cicciarella, Michael Krutzen, Emanuele Rodolà and Silvia Zuffi. This work was presented at the CV4Animals workshop at CVPR 2025.

Upload the notebook to your Drive, open with Colab, and upload the zip file to the `content/` folder once you're connected to a runtime.

**WARNING**: you need a GPU runtime to run the experiments in the notebook, as `kaolin` only supports CUDA backends for differentiable rendering.
