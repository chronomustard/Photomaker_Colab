# Photomaker

Welcome to Photomaker Colab repository! This repository hosts the codebase for a Google Colab Notebook implementation of Photomaker. Photomaker the customization of realistic human photos via stacked ID embedding to generate high-quality images with various styles and characteristics.

🐣 Please follow me for new updates [here](https://github.com/chronomustard)

## Colab

| Colab | Info |
| --- | --- |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nHI8cKiAdU4nIg5tOSgRvtncvzMcygjw?usp=sharing) | PhotoMaker_colab (Pro Colab using A40 or V40 😐) |

Access our Colab notebook for easy experimentation with Photomaker. This Colab notebook is optimized for use with A40 or V40 GPUs.

## Code

Find the complete source code for Photomaker in this repository:

[https://github.com/TencentARC/PhotoMaker](https://github.com/TencentARC/PhotoMaker)

## Paper

Read about the underlying methodology and research behind Photomaker in the research paper:

[https://arxiv.org/abs/2312.04461](https://arxiv.org/abs/2312.04461)

## Page

Visit the official project page for more information and updates:

[https://photo-maker.github.io/](https://photo-maker.github.io/)

## Requirements

To run Photomaker, ensure you have the following dependencies installed:

- torch==2.0.1
- torchvision==0.15.2
- diffusers==0.25.0
- transformers==4.36.2
- huggingface-hub==0.20.2
- spaces==0.19.4
- numpy
- accelerate
- safetensors
- omegaconf
- peft
- gradio>=4.0.0

## Acknowledgements
- PhotoMaker is co-hosted by Tencent ARC Lab and Nankai University [MCG-NKU](https://mmcheng.net/cmm/).
- Inspired from many excellent demos and repos, including [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [multimodalart/Ip-Adapter-FaceID](https://huggingface.co/spaces/multimodalart/Ip-Adapter-FaceID), [FastComposer](https://github.com/mit-han-lab/fastcomposer), and [T2I-Adapter](https://github.com/TencentARC/T2I-Adapter). Thanks for their great work!
- Thanks to the Venus team in Tencent PCG for their feedback and suggestions.
- Thanks to the HuggingFace team for their generous support! 

## Disclaimer
This project strives to impact the domain of AI-driven image generation positively. Users are granted the freedom to create images using this tool, but they are expected to comply with local laws and utilize it responsibly. The developers do not assume any responsibility for potential misuse by users.

## BibTeX
If you find PhotoMaker useful for your research and applications, please cite using this BibTeX:

```BibTeX
@article{li2023photomaker,
  title={PhotoMaker: Customizing Realistic Human Photos via Stacked ID Embedding},
  author={Li, Zhen and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Cheng, Ming-Ming and Shan, Ying},
  booktitle={arXiv preprint arxiv:2312.04461},
  year={2023}
}
