# GAN-Deepfakes
 Conditional face generation experiments using GAN models on CelebA dataset. Usage of exponential moving average (EMU)
## Architectures
* Normal DCGAN architecture
* Normal model with EMU training

## EMU Training
Idea from https://arxiv.org/abs/1806.04498.

wt+1 = (1 - b) * ut + (b) * wt  

No EMU:
![image](https://github.com/MarinaGalanina/GAN-Deepfakes/assets/100734139/eb463847-70d0-43b8-a907-46354a66927f)

EMU:
![image](https://github.com/MarinaGalanina/GAN-Deepfakes/assets/100734139/d2966f71-4942-4d37-ae3d-b006b01ad5a7)

