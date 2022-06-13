# Generative Deep Learning
![](https://img.shields.io/badge/TensorFlow%20Faculty%20Award-2021%20Winner-orange.svg)

Code repository for the PhD course of [**Generative Deep Learning**](https://danilocomminiello.site.uniroma1.it/teaching/gdl), 3 CFU (18 hours), edition 2021/2022.

Instructor: Prof. Danilo Comminiello :man_teacher:

## Seminars :office_worker:

### Imagen: imagine · illustrate · inspire
#### Chitwan Saharia, Google Brain.

Tuesday 21st, 4:00 pm, [Zoom Link](https://uniroma1.zoom.us/j/86596351314?pwd=T0pja1RKLzFTd2ZabWN0TS9yN2tMQT09).

**Abstract**

Imagen is a text-to-image diffusion model with an unprecedented degree of photorealism and a deep level of language understanding. Imagen builds on the power of large transformer language models in understanding text and hinges on the strength of diffusion models in high-fidelity image generation. Our key discovery is that generic large language models (e.g. T5), pretrained on text-only corpora, are surprisingly effective at encoding text for image synthesis: increasing the size of the language model in Imagen boosts both sample fidelity and image-text alignment much more than increasing the size of the image diffusion model. Imagen achieves state-of-the-art results in COCO without ever training on COCO, and, when compared with recent methods including VQ-GAN+CLIP, Latent Diffusion Models, and DALL-E 2, human raters prefer Imagen over other models in side-by-side comparisons, both in terms of sample quality and image-text alignment.

**Bio**

Chitwan Saharia is a Research Engineer at Google Brain, Toronto. He finished his undergrad at the Indian Institute of Technology (IIT), Bombay with a major in Computer Science and Engineering. He interned at Mila, Montreal under the supervision of Prof. Yoshua Bengio, and Dzmitry Bahdanau.
His research interests are mainly diffusion-based image generative models. He has also been actively working on non-autoregressive generative models for text. As an undergrad, he interned at MILA and worked on analyzing sample complexity of learning algorithms for grounded language learning.


### Creating noise from data is easy; creating data from noise is generative modeling
#### Yang Song, Stanford AI Lab.

Monday 27th, 5:30 pm, [Zoom Link](https://uniroma1.zoom.us/j/86596351314?pwd=T0pja1RKLzFTd2ZabWN0TS9yN2tMQT09).

**Abstract**

Creating noise from data is easy; creating data from noise is generative modeling. We will see a stochastic differential equation (SDE) that smoothly transforms a complex data distribution to a known prior distribution by slowly injecting noise and a corresponding reverse-time SDE that transforms the prior distribution back into the data distribution by slowly removing the noise. Crucially, the reverse-time SDE depends only on the time-dependent gradient field (a.k.a., score) of the perturbed data distribution. By leveraging advances in score-based generative modeling, it is possible to accurately estimate these scores with neural networks, and use numerical SDE solvers to generate samples. This framework encapsulates previous approaches in score-based generative modeling and diffusion probabilistic modeling, allowing for new sampling procedures and new modeling capabilities. In addition, this method provides a new way to solve inverse problems with score-based models, as demonstrated with experiments on class-conditional generation, image inpainting, and colorization. Combined with multiple architectural improvements, the approach achieves record-breaking performance for unconditional image generation, a competitive likelihood, and demonstrates high fidelity generation of 1024 x 1024 images for the first time from a score-based generative model.

**Bio**

Yang Song is a final-year Ph.D. student in Computer Science at Stanford University, advised by Stefano Ermon. He obtained his Bachelor’s degree in Mathematics and Physics from Tsinghua University. He was a research intern at Google Brain, Uber ATG, and Microsoft Research. He was awarded with the Outstanding Paper Award at the 9th International Conference on Learning Representations (ICLR) in 2021 for his paper “Score-Based Generative Modeling through Stochastic Differential Equations”.
His research focuses on the foundations of deep generative models, as well as their applications to AI safety, inverse problems, and their impacts on the broader field of machine learning. He has made several key contributions to the mathematical formulation and empirical performance of score-based generative models. 
