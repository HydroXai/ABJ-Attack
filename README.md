# ABJ-Attack
This repository contains the official implementation of our paper "[Figure it Out: Analyzing-based Jailbreak Attack on Large Language Models](https://arxiv.org/pdf/2407.16205)"

[![arXiv: paper](https://img.shields.io/badge/arXiv-paper-red.svg)](https://arxiv.org/abs/2407.16205)
![Jailbreak Attacks](https://img.shields.io/badge/Jailbreak-Attacks-yellow.svg?style=plastic)
![Large Language Models](https://img.shields.io/badge/LargeLanguage-Models-green.svg?style=plastic)
[![license: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Please feel free to contact linshizjsu@gmail.com if you have any questions.

## Table of Contents

- [Updates](#updates)
- [Overview](#overview)
- [Quick Start](#Quick Start)


## Updates

- (**2024/07/23**) We have released the official code of ABJ-Attack!
- (**2024/07/23**) Our paper is on arXiv! Check it out [here](https://arxiv.org/abs/2407.16205)!


## Overview

This repository shares the code of our latest work on LLMs jailbreaking. In this work:

- We further explore the boundary of jailbreak attacks on LLMs and propose ABJ, the first jailbreak attack method specifically designed to assess LLMs’ safety in handling analyzing-based tasks. ABJ generalizes jailbreak attack prompts in two steps: data preparation and data analysis.
- We conduct comprehensive experiments on both open-source (Llama-3, Qwen-2, GLM-4) and closed-source (GPT-3.5-turbo, GPT-4-turbo, Claude-3) LLMs. The results demonstrate that ABJ exhibits exceptional attack effectiveness and efficiency, achieving 94.8% ASR on GPT-4-turbo, while the AE is around 1. 
- We show the robustness of ABJ when facing different defense strategies, indicating that mitigating this attack might be difficult. Furthermore, by modifying and enriching the data of ABJ, we induce LLMs to generate a wide range of harmful content, encompassing various forms of harmful scenarios that are not limited to existing finite datasets.

# Quick Start


## Citation

If you find this work useful in your own research, please feel free to leave a star⭐️ and cite our paper:

```bibtex
@misc{lin2023abj,
      title={Figure it Out: Analyzing-based Jailbreak Attack on Large Language Models}, 
      author={Shi Lin and Rongchang Li and Xun Wang and Changting Lin and Wenpeng Xing and Meng Han},
      year={2024},
      journal={arXiv preprint arXiv:2407.16205}
}
```
