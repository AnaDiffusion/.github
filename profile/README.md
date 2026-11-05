<div align="center">

<h1>AnaDiffusion</h1>

<p><strong>Anatomically Compositional Latent Diffusion for Controllable 3D Brain MRI Generation</strong></p>

<p>
  <a href="https://arxiv.org/abs/2608.23014"><img src="https://img.shields.io/badge/arXiv-2608.23014-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv"></a>
  <a href="https://github.com/phai-lab/AnaDiffusion"><img src="https://img.shields.io/badge/GitHub-Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"></a>
  <a href="https://anadiffusion.github.io"><img src="https://img.shields.io/badge/Project-Page-2F80ED?style=for-the-badge&logo=githubpages&logoColor=white" alt="Project Page"></a>
</p>

<img src="https://anadiffusion.github.io/images/figure-2-method.png" alt="AnaDiffusion method overview" width="100%">

</div>

**AnaDiffusion** composes whole-brain MRI generation from anatomical part models. The model first synthesizes high-fidelity regional parts and assembles them into a whole-brain scaffold. The scaffold is re-encoded into the whole-brain latent space and injected during denoising, enabling local anatomical detail and globally coherent whole-brain synthesis.

- **Code:** [phai-lab/AnaDiffusion](https://github.com/phai-lab/AnaDiffusion)
- **Paper:** [arXiv:2608.23014](https://arxiv.org/abs/2608.23014)
- **Project page:** [anadiffusion.github.io](https://anadiffusion.github.io)

```bibtex
@article{han2026anadiffusion,
  title={AnaDiffusion: Anatomically Compositional Latent Diffusion for Controllable 3D Brain MRI Generation},
  author={Han, Huiwen and Liu, Lulin and Liu, Bangya and Cai, Yuanhao and Chen, Nuo and Wang, Xiaoqing and Xie, Ziqian and You, Chenyu and Ji, Shuiwang and Zhi, Degui and others},
  journal={arXiv preprint arXiv:2608.23014},
  year={2026}
}
```
