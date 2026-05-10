# SCALE: Self-uncertainty Conditioned Adaptive Looking and Execution for Vision-Language-Action Models (ICML 2026 Spotlight)

Official implementation of **"SCALE: Self-uncertainty Conditioned Adaptive Looking and Execution for Vision-Language-Action Models"** (ICML 2026 **Spotlight**).

[`Hyeonbeom Choi`](https://hyeonbeomchoi.github.io)\* | [`Daechul Ahn`](https://dcahn12.github.io/)\* | [`Youhan Lee`](https://youhanlee.github.io) | [`Taewook Kang`](https://twkang43.github.io) | [`Seongwon Cho`](https://seongwon980.github.io/) | [`Jonghyun Choi`](https://ppolon.github.io/)†

<sub><span style="color:gray">\* Equal contribution &nbsp;&nbsp; † Corresponding author</span></sub>

## 🧭 Overview

> **TL;DR.** VLA models have emerged as a promising paradigm for general-purpose robotic control, with test-time scaling (TTS) gaining attention to enhance robustness beyond training. However, existing TTS methods require additional training, verifiers, and multiple forward passes, making them impractical for deployment. Moreover, they intervene only at action decoding while keeping visual representations fixed—insufficient under perceptual ambiguity. We propose **SCALE**, a simple inference strategy that jointly modulates visual perception and action based on self-uncertainty, inspired by Active Inference theory—requiring no additional training, no verifier, and only a single forward pass.

[[Paper]](https://arxiv.org/pdf/2602.04208) [[Project Page]](https://dcahn12.github.io/projects/scale/)

## 🔊 Updates

- [x] Release the paper on <a href="https://arxiv.org/abs/2602.04208">arXiv</a> <br>
- [x] Open the <a href="[https://dcahn12.github.io/projects/rtsbench/](https://dcahn12.github.io/projects/scale/)">project page</a> for SCALE! <br>
- [ ] Release the evaluation code for SCALE <br>


#### Code coming soon! Stay tuned.

## Citation

```bibtex
@article{choi2026scale,
  title={SCALE: Self-uncertainty Conditioned Adaptive Looking and Execution for Vision-Language-Action Models}, 
  author={Hyeonbeom Choi and Daechul Ahn and Youhan Lee and Taewook Kang and Seongwon Cho and Jonghyun Choi},
  journal={ICML},
  year={2026}
}
```
