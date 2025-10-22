<h3 align="center">
    MoGA: Mixture-of-Groups Attention for End-to-End Long Video Generation
</h3>

<p align="center"> 
<a href="https://jiawn-creator.github.io/mixture-of-groups-attention/"><img alt="Build" src="https://img.shields.io/badge/Project%20Page-MoGA-blue"></a>
<a href="https://arxiv.org/pdf/2510.18692"><img alt="Build" src="https://img.shields.io/badge/Paper-MoGA-b31b1b.svg"></a>


><p align="center"> <span style="color:#137cf3; font-family:Gill Sans">Weinan Jia</span>, <span style="color:#137cf3; font-family:Gill Sans">Yuning Lu<sup>+</sup></span>, <span style="color:#137cf3; font-family:Gill Sans">Mengqi Huang</span><br> <span style="color:#137cf3; font-family:Gill Sans">Hualiang Wang</span>, <span style="color:#137cf3; font-family:Gill Sans">Binyuan Huang</span>, <span style="color:#137cf3; font-family:Gill Sans">Nan Chen</span>, <span style="color:#137cf3; font-family:Gill Sans">Mu Liu</span>, <span style="color:#137cf3; font-family:Gill Sans">Jidong Jiang</span>, <span style="color:#137cf3; font-family:Gill Sans">Zhendong Mao<sup>+</sup></span></a> <br>




## 🔥 News
- [10/22/2025] 🔥 The arXiv [paper](https://arxiv.org/pdf/2510.18692) of MoGA is released.
- [10/22/2025] 🔥 The [project page](https://jiawn-creator.github.io/mixture-of-groups-attention/) of MoGA is created.

## 📖 Introduction
<p align="center">
<img src="assets/framework.png" width=95% height=95% 
class="center">
</p>
We introduce <b>MoGA</b>, an efficient sparse attention for end-to-end long video generation. The overall architecture is shown above.
<p align="center">
<img src="assets/motivation.png" width=95% height=95% 
class="center">
</p>

Through semantic-aware routing, MoGA enables effective long-range interactions. As a kernel-free method, MoGA integrates seamlessly with modern attention stacks, including FlashAttention and sequence parallelism. Building on MoGA, we develop an efficient long video generation model that end-to-end produces minute-level, multi-shot, 480p videos at 24 fps, with a context length of approximately 580k. Comprehensive experiments on various video generation tasks validate the effectiveness of our approach.
<p align="center">
<img src="assets/appendix_1441.png" width=95% height=95% 
class="center">
</p>

## 🚀 Updates
To support research and the open-source community, we will release the entire project—including inference pipelines, and model weights. Thank you for your patience and continued support! 🌟
- [x] Release arXiv paper
- [x] Release GitHub repo
- [ ] Release inference code
- [ ] Release model checkpoints
