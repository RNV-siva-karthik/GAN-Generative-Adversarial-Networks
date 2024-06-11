One of the most prominent approach for Generative AI is the use of GAN's or Generative Adversarial Networks. 
The architecture of a GAN is very intriguing, it consists of a generator and a discriminator, the job of a generator is to make an image from noise vector or latent vector and the discriminator is trained to distinguish the real and generated images. 
Then the loss is computed and both the parts the generator and discriminator weights are finetuned (discriminator is trained first and it is not trainable while the generator is being trained).
One extension to such an architecture is conditional GAN where it is tasked to generate images from a predefined condition in the form of a label, text embedding, etc... 
💈 Making a random image from some random noise might not be the ideal use case. would it? but they require a lot of training. 
🤖 one of the example use case where GAN is used is in DALL-E but it is enhanced with the power of transformers, not the ones from the movie but the ones from neural networks. this made it very powerful in text to image generation. 
🕯 Although diffusion models are also great at this but GANs are a little faster as they iterate once through generator and discriminator but not several times through the network as in diffusion models.
