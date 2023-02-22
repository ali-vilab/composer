# Composer

Official repo for [Composer: Creative and Controllable Image Synthesis with Composable Conditions](https://arxiv.org/abs/2302.09778).

See [Project Page](https://damo-vilab.github.io/composer-page/) for more examples.

![Concept of Composer](assets/teaser.jpg "Concept of Composer")
<!-- *(Concept of Composer)* -->

Composer is a large (5 billion parameters) controllable diffusion model trained on billions of (text, image) pairs. It can exponentially expand the control space through composition, leading to an enormous number of ways to generate and manipulate images, i.e., making *the infinite use of finite means*.


## TODO

- [ ] Release training and inference code.
- [ ] Release pretrained models.
- [ ] Release Gradio UI.
- [ ] A light-weighted Latent-Composer built upon Stable Diffusion 2.0.


## Composition Results

### Composition of **text** and **depth**.

![Text+Depth](assets/text+depth.jpg "Text+Depth")

### Composition of **masked image** and **text**.

![Masking+Text](assets/masking+text.jpg "Masking+Text")

### Composition of **sketch, depth** and **embedding** (1).

![Sketch,Depth+Embedding](assets/sketch,depth+embedding_1.jpg "Sketch,Depth+Embedding")

### Composition of **sketch, depth** and **embedding** (2).

![Sketch,Depth+Embedding](assets/sketch,depth+embedding_2.jpg "Sketch,Depth+Embedding")

### Composition of **text** and **palette**.

![Text+Palette](assets/text+palette.jpg "Text+Palette")

### Composition of **embedding** and **palette**.

![Embedding+Palette](assets/embedding+palette.jpg "Embedding+Palette")

### Composition of **intensity** and **palette**.

![Intensity+Palette](assets/intensity+palette.jpg "Intensity+Palette")


## Manipulation Results

### **Image variations** when fixing **sketch, depth, palette** and/or **embedding**.

![Image Variations](assets/variations.jpg "Image Variations")

### **Image interpolations** when fixing **sketch, depth, segmentation map** and/or **palette**.

![Image Interpolations](assets/interpolations.jpg "Image Interpolations")

### **Image reconfigurations** (manipulating an image by directly modifying its elements).

![Image Reconfigurations](assets/reconfigurations.jpg "Image Reconfigurations")

### **Color interpolations.**

![Color Interpolations](assets/color_interpolations.jpg "Color Interpolations")

### **Region-specific image editing.**

![Region-specific image editing](assets/editable_region.jpg "Region-specific image editing")


## Reformulation of Classical Tasks

### **Image translation.**

![Image Translation](assets/translation.jpg "Image Translation")

### **Style transfer.**

![Style Transfer](assets/style_transfer.jpg "Style Transfer")

### **Pose transfer.**

![Pose Transfer](assets/pose_transfer.jpg "Pose Transfer")

### **Virtual try-on.**

![Virtual Try-on](assets/virtual_try_on.jpg "Virtual Try-on")


## BibTeX

```bibtex
@article{lhhuang2023composer,
  title={Composer: Creative and Controllable Image Synthesis with Composable Conditions},
  author={Huang, Lianghua and Chen, Di and Liu, Yu and Yujun, Shen and Zhao, Deli and Jingren, Zhou},
  booktitle={arXiv preprint arxiv:2302.09778},
  year={2023}
}
```
