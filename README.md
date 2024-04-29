# Awesome list of vertebral labeling methods

This repository will be used to track and regroup most/all the relevant methods used for vertebral labeling on MRI and CT scans.

## List

| Method name | Link | Open source | Task | Region | Modality | Deep Learning based | Date | Comments |
| :-------------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Template-based approach | [paper](https://dl.acm.org/doi/abs/10.1155/2014/719520) | [Yes](https://github.com/spinalcordtoolbox/spinalcordtoolbox) | Discs detection | Disc C2-C3 must be visible | MRI (T1w/ T2w) | No | 2014 | Do not work when the FOV is thoracic or lumbar |
| Spine-GAN | [paper](https://www.sciencedirect.com/science/article/pii/S136184151830642X) | No | Discs, vertebrae and neural foramen segmentation | Lumbar | MRI (T1w/ T2w) | Yes | 2018 | |
| Spine-explorer | [paper](https://www.sciencedirect.com/science/article/pii/S1529943019311064?via%3Dihub) | No | Vertebrae and discs segmentation | Lumbar | MRI (T2w) | Yes | 2020 | |
| Stacked hourglass | [paper](https://arxiv.org/abs/2108.06554) | [Yes](https://github.com/rezazad68/Deep-Intervertebral-Disc-Labeling) | Discs detection | Cervical FOV | MRI (T1w/ T2w) | Yes (Hourglass) | 2021 | Restricted to a specific FOV |
| SpineNetV2 | [paper](https://arxiv.org/pdf/2205.01683.pdf) | [Yes](https://github.com/rwindsor1/SpineNet#install-enviroments) | Vertebral bodies detection/ radiological grading | Whole spine | MRI (T1w/ T2w/ STIR/ TIRM) | Yes | 2022 | Strange behaviour with T1w scans |
| Spine-transformers | [paper](https://www.sciencedirect.com/science/article/pii/S1361841521003030) | No | Vertebrae segmentation | Whole spine | CT | Yes | 2022 | |
| Total segmentator | [paper](https://arxiv.org/abs/2208.05868) | [Yes](https://github.com/wasserth/TotalSegmentator) | Global segmentation | Whole body | CT | Yes (nnUNet) | 2022 |  |
| HCA-NET | [paper](https://arxiv.org/abs/2311.12486) | [Yes](https://github.com/xmindflow/HCA-Net) | Discs detection | Cervical FOV | MRI (T1w/ T2w) | Yes | 2023 | Restricted to a specific FOV |
| MRI to CT registration then segmentation | [paper](https://link.springer.com/article/10.1186/s41747-023-00385-2) | [Yes](https://github.com/robert-graf/Pointregistation) | Vertebrae and discs segmentations | Whole spine | MRI (T1w/ T2w) | Yes (Pix2Pix) | 2023 | Relying on VerSe and [SpineR](https://www.bonescreen.de/anduin) |
| Vertebrae segmentation with anatomic consistency cycle | [paper](https://www.sciencedirect.com/science/article/pii/S0895611123000538?ref=pdf_download&fr=RR-2&rr=864ebae549544bd0) | [Yes](https://gitlab.inria.fr/spine/vertebrae_segmentation) | Vertebrae segmentation | Whole spine | CT | Yes | 2023 |  |
| SPINEPS | [paper](https://paperswithcode.com/paper/spineps-automatic-whole-spine-segmentation-of) | [Yes](https://github.com/hendrik-code/spineps) | Vertebrae and discs segmentations | Whole spine | T2w | Yes (nnUNetV2) | 2024 | No label identification but accurate instance segmentation |

## See also

NeuroPoly disc labeling implementations:
- Disc labeling benchmark: https://github.com/spinalcordtoolbox/disc-labeling-benchmark
- Hourglass approach: https://github.com/spinalcordtoolbox/disc-labeling-hourglass
- nnU-Net approach: https://github.com/spinalcordtoolbox/disc-labeling-nnunet

## Other public methods

- [VerSe](https://github.com/anjany/verse): A vertebrae labelling and segmentation benchmark for multi-detector CT images.
- [Panoptica](https://github.com/BrainLesion/panoptica): Public package to evaluate instance segmentations methods.

## Contributions and Feedback

Contributions to this repository are welcome. If you have developed a new method or have improvements to existing methods, please submit a pull request. Additionally, feedback and suggestions for improvement are highly appreciated. Feel free to open an issue to report problems, propose new methods, or ask questions.

