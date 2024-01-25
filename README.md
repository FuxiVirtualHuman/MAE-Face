# MAE-Face: A Generic Facial Representation Model

Welcome to the official repository of MAE-Face, a pre-trained model designed for generic facial representation.

## About MAE-Face

MAE-Face leverages masked autoencoders, a self-supervised learning approach, on large-scale facial datasets to learn robust facial representation.

MAE-Face has achieved state-of-the-art performance for facial affective analysis across multiple datasets, including BP4D, DISFA, AffectNet, RAF-DB, Aff-Wild2, and Emo135, etc.

Moreover, its application is not restricted to facial affective analysis.
Its versatility has the potential to extend to various facial tasks.
It is welcome for you to explore the potential of MAE-Face and share your findings with us (through issues or [contact us](#contact)).

### Reference papers
- [Facial Action Unit Detection and Intensity Estimation from Self-supervised Representation](https://arxiv.org/abs/2210.15878)
- [A Unified Approach to Facial Affect Analysis: the MAE-Face Visual Representation](https://openaccess.thecvf.com/content/CVPR2023W/ABAW/html/Ma_A_Unified_Approach_to_Facial_Affect_Analysis_The_MAE-Face_Visual_CVPRW_2023_paper.html)

## Getting Started

To use MAE-Face, clone this repository and install the required dependencies:
- [PyTorch](https://pytorch.org/)
- [timm](https://timm.fast.ai/)

To use the pre-trained MAE-Face model, download the `.pth` files from the [Releases](https://github.com/FuxiVirtualHuman/MAE-Face/releases) section.
Use `models_vit.py` to create the model, and load the pre-trained weights from the `.pth` files.
You can refer to `example.py`, which shows a simple example about how to load the pre-trained model.

For more details, please refer to the orignial [MAE](https://github.com/facebookresearch/mae) repository.
For example, use `main_finetune.py` to fine-tune MAE-Face on your own dataset, or use `main_pretrain.py` for further pre-training.

## Citation

If you use the above models, please cite the following papers:

```
@article{ma2022facial,
  title={Facial Action Unit Detection and Intensity Estimation from Self-supervised Representation},
  author={Ma, Bowen and An, Rudong and Zhang, Wei and Ding, Yu and Zhao, Zeng and Zhang, Rongsheng and Lv, Tangjie and Fan, Changjie and Hu, Zhipeng},
  journal={arXiv preprint arXiv:2210.15878},
  year={2022}
}

@inproceedings{ma2023unified,
  title={A Unified Approach to Facial Affect Analysis: The MAE-Face Visual Representation},
  author={Ma, Bowen and Zhang, Wei and Qiu, Feng and Ding, Yu},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={5923--5932},
  year={2023}
}
```

## Contact

[Bowen Ma](mailto:sanma.kote@gmail.com)
