# Cycle-GAN

### Overview:
In this project, we're going to define and train a CycleGAN to read in an image from a set 𝑋 and transform it so that it looks as if it belongs in set 𝑌. Specifically, we'll look at a set of images of Yosemite national park taken either during the summer of winter. The seasons are our two domains!
These images do not come with labels, but CycleGANs give us a way to learn the mapping between one image domain and another using an unsupervised approach. A CycleGAN is designed for image-to-image translation and it learns from unpaired training data. This means that in order to train a generator to translate images from domain 𝑋 to domain 𝑌, we do not have to have exact correspondences between individual images in those domains. For example, in the paper that introduced CycleGANs, the authors are able to translate between images of horses and zebras, even though there are no images of a zebra in exactly the same position as a horse or with exactly the same background, etc. Thus, CycleGANs enable learning a mapping from one domain 𝑋 to another domain 𝑌 without having to find perfectly-matched, training pairs!

### Requirements:
Python 3.x
