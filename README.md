GAN-generated NFT Collection
============================
![image](https://github.com/agulati18/GAN-Generated-NFT-Collection/assets/67696969/7542871f-ced0-43df-8ad8-734ed94b4c8d)

Team: Aryaman Gulati, Ben Eibl, Kartikeya Agarwal

Introduction:
-------------

The aim of this project was to explore the application of Generative Adversarial Networks (GANs) to the creation of a new NFT collection on the blockchain. Due to the limitations of time and resources, the team generated a 'lite' version of the collection using existing crypto collections, namely Crypto Punks and Crypto Corgis.

Exploration:
------------

The team explored various ideas, including equity-pricing algorithms and football player transfer valuation models. However, we  were particularly interested in the world of Web3 and NFTs, given the recent discussion of GANs in class. We decided to use GANs to generate a new NFT collection and eventually put it on the blockchain. However, we  faced a setback when we could not access OpenSea's API due to recent changes, which required users to have digital wallets. As a result, we opted to use the Crypto Punk series, which was available on GitHub, and later included the Crypto Corgis collection.

Methodology:
------------

The team spent the first week familiarizing themselves with Tensorflow and the GAN set up, including the generator, discriminator, loss function, and outputs. We then collected data from the Crypto Punk and Crypto Corgi collections and implemented the GAN in week three to create 16 new images based on each collection. The generator and discriminator networks are defined, and loss functions are calculated for each network. The generator_optimizer and discriminator_optimizer are used to optimize the networks during training. The training loop generates and saves new images and trains the networks on real and fake images. The script outputs a GIF of the generated images. We experimented with input parameters, such as batch size, epochs, and image pixels, and found that smaller batch sizes and more epochs created better outputs. We also adapted the code to include the Crypto Corgis in the cycle GAN, and used a lot more epochs than the guide did to create better outputs.

Results:
--------

The team generated a non-extensive collection of GAN-generated NFTs, and the output was almost believable as part of the original collections. Figures 1a and 1b show the Crypto Punks and Crypto Corgis generated after 500 epochs, respectively, while Figures 2a and 2b show the Cryptopunk style Cryptocorgis and Cryptocorgi style Cryptopunks, respectively, generated from the CycleGAN after 200 epochs. Although the style transfer did not work as well as expected in some cases, it produced some interesting outputs, such as using features from the source, such as sunglasses, on the output.


Extensions:
-----------

With more time, the team would have loved to explore other forms of GANs, such as SinGANs, to generate NFTs/images from a single image. We  would also have liked to use CycleGANs on other collections found online, but this would require obtaining an API key by setting up a digital wallet and some cryptocurrency. Finally, we considered using a similar approach to create new NFT collections from famous soccer players or paintings.

Takeaways and Learnings:
------------------------

The skills and knowledge gained from this project are highly relevant in the current landscape of emerging technologies such as Web3 and blockchain, where NFTs and GANs are becoming increasingly popular. Understanding the technical aspects of GANs and neural networks is crucial in developing applications that utilize these technologies. Additionally, the knowledge gained from this project will be  useful in future projects involving computer vision and image analysis.

During the course of this project, we delved into the world of Generative Adversarial Networks (GANs), which are a class of deep learning algorithms that can be used for generating new data. We learned about the basic architecture of a GAN, which involves a generator network that tries to create realistic images and a discriminator network that tries to distinguish between the generated images and real images. Through training the generator and discriminator together, GANs can create highly realistic images that can be used for a variety of purposes, including art generation, image super-resolution, and data augmentation.

In particular, we gained hands-on experience using frameworks like Tensorflow to implement GANs and train them on different datasets. We also learned about the various hyperparameters that can be adjusted to improve the performance of a GAN, such as the learning rate, batch size, and number of epochs. This knowledge will be useful in future projects involving deep learning and neural networks.

Another important aspect of this project was working with APIs to access data. We learned about the different types of APIs that are available, including RESTful APIs and GraphQL APIs, and how to use them to extract data from external sources. Specifically, we worked with NFT collections and learned how to use the OpenSea API to extract information about NFTs, such as their metadata and images. This experience will be valuable in future projects involving data analysis and extraction.

Lastly, we gained experience with image processing techniques and convolutional neural networks (CNNs), which are a type of neural network that is commonly used for image classification and generation tasks. We learned how to preprocess images to make them suitable for training a CNN and how to use different types of layers, such as convolutional layers, pooling layers, and fully connected layers, to build a CNN architecture.

Conclusion:
-----------

Despite the setbacks faced by the team, the project allowed them to delve into an area of interest in-depth and explore the application of GANs in the world of Web3 and NFTs. Although we generated a preview of the collection, we were pleased with the output and hope to develop it further in the future.
