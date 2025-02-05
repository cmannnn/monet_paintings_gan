# Monet Paintings GAN

The "I'm Somethigng of a Painter Myself" Kaggle project is a project that ranks participants on their ability to best mimick the style of the popular aritst Claude Monet by using generative adversarial networks (GANs). The GAN created in this notebook will need to produce 7,000 - 10,000 Monet-style images. There are two sources of data for this competition. The first dataset is the true Monet paintings, which are available in both .jpg and .tfrec formats for usability. There is a secondary dataset that consists of pictures of various landscapes, cities, animals, etc. These are the pictures that will be transformed to Monet's style.

The submissions will be evaluated on the MiFID (Memorization-informed Fréchet Inception Distance), which is modified from Fréchet Inception Distance (FID) score and is commonly used to evaluate the ability of GANs. The lower the MiFID score the better.
