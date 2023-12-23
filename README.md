# DELIP
DELIP: Dense Enhanced Language-Image Pretraining - Official Implementation

## News 📢

- **[2023-12-23]** - Our preliminary base model, `delip-vit-large-512-v0.1`, is now available. Check it out here: [delip-vit-large-512-v0.1](https://huggingface.co/Zhiyuan-Fan/delip-vit-large-512-v0.1).

- **[2023-12-23]** - 🚀 Launched the DELIP code repository! We are currently organizing the code and data for easy open-source access. Additionally, we are excited to announce that our paper detailing the DELIP project is in the final stages of preparation and will be published soon. Stay tuned! 🌟



## Introduction

In this project, we have gathered a large number of high-quality `<image, dense caption>` pairs. By initializing with the CLIP model, we've conducted continue pre-training to enhance model's capabilities. A key improvement in our method is increasing the token limit from 77 to 2k. This expansion allows our model to handle more detailed and precise alignments between images and text.

## Citation

If you find DELIP useful in your research, please consider citing our work:

```bibtex
@misc{DELIP2023,
  title={DELIP: Dense Enhanced Language-Image Pretraining},
  author={Zhiyuan Fan and Zhihong Chen and Benyou Wang},
  year={2023},
  publisher={GitHub},
  journal={GitHub repository},
  howpublished={\url{https://github.com/Elvisambition/DELIP}}
}

```
