# EECS504_Project
This project aims to implement unpaired image-to-image

translation by reproducing cycle-consistent adversarial net-
works (CycleGAN) model implemented by Jun-Yan Zhu

et al. Using the Horse2zebra dataset from UC Berke-
ley’s repository, we have successfully generated images for

horse-to-zebra and zebra-to-horse tasks. We have tried U-
net and ResNet blocks as the generators and Nlayer and

Pixel blocks as the discriminators. We have used visual in-
spection and the FID metric to evaluate the performance of

our implementation. The experimental results show that the
ResNet-9 generator and the N-layer discriminator produces
superior quality images.
