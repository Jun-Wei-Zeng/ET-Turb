# <div align="center"> ET-Turb: Continuous Exposure-Time Modeling for Realistic Atmospheric Turbulence Synthesis </div>

<div align="center">
  <a href="https://github.com/Jun-Wei-Zeng/ET-Turb"><img src="https://img.shields.io/static/v1?label=Code&message=Github&color=blue&logo=github"></a> &ensp;
  <a href="https://github.com/Jun-Wei-Zeng/ET-Turb"><img src="https://img.shields.io/static/v1?label=Project%20Page&message=Github&color=blue&logo=github-pages"></a> &ensp;
  <a href="https://arxiv.org/abs/2603.01398"><img src="https://img.shields.io/static/v1?label=arXiv&message=2603.01398&color=b31b1b&logo=arxiv"></a> &ensp;
  <a href="https://cvpr.thecvf.com/Conferences/2026"><img src="https://img.shields.io/static/v1?label=CVPR&message=2026&color=green"></a> &ensp;
  <a href=""><img src="https://img.shields.io/static/v1?label=Dataset&message=Will%20be%20released&color=yellow"></a>
</div>

<div align="center">

Junwei Zeng, Dong Liang, Sheng-Jun Huang, Kun Zhan, Songcan Chen

Nanjing University of Aeronautics and Astronautics &nbsp; | &nbsp; Lanzhou University

</div>

---

## &#128226; Breaking News

- [Mar. 2026] ET-Turb was accepted by [CVPR 2026](https://cvpr.thecvf.com/Conferences/2026).
- [Mar. 2026] ET-Turb was uploaded to [arXiv](https://arxiv.org/abs/2603.01398).

Star &#127775; us if you think it is helpful!

## &#9989; Todo List

- [ ] Release the ET-Turb dataset.

## &#129303; Dataset Download

| Dataset | Status |
| --- | ---: |
| ET-Turb | Will be released |

ET-Turb contains **5,083 videos** and **2,005,835 frames**, with **3,988 training videos** and **1,095 test videos**. Exposure-time is continuously sampled from **0.5 ms to 40 ms** across 12 optical and atmospheric configurations.

## &#128202; No-Reference Real-Turbulence Evaluation

Lower NIQE and BRISQUE scores are better.

| Training Dataset | TSR-WGAN NIQE | TSR-WGAN BRISQUE | TMT NIQE | TMT BRISQUE | DATUM NIQE | DATUM BRISQUE | MambaTM NIQE | MambaTM BRISQUE |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| TMT-dynamic | 4.231 | 52.502 | 4.361 | 58.581 | 4.219 | 54.921 | 4.217 | 55.062 |
| ATSyn-dynamic | 4.224 | 54.462 | 4.483 | 59.707 | 4.308 | 59.126 | 4.247 | 56.876 |
| **ET-Turb** | **4.190** | **50.981** | **4.221** | **56.691** | **4.204** | **54.070** | **4.212** | **55.050** |

## &#128221; Citation

```bibtex
@inproceedings{zeng2026continuous,
  title={Continuous Exposure-Time Modeling for Realistic Atmospheric Turbulence Synthesis},
  author={Zeng, Junwei and Liang, Dong and Huang, Sheng-Jun and Zhan, Kun and Chen, Songcan},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={26678--26687},
  year={2026}
}
```
