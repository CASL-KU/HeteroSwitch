# HeteroSwitch Dataset

## Research Paper
The foundational research, "HeteroSwitch: Characterizing and Taming System-Induced Data Heterogeneity in Federated Learning," is available at [arXiv](https://arxiv.org/abs/2403.04207). This work was presented at the 7th Annual Conference on Machine Learning and Systems (MLSys 2024), contributing significantly to the understanding and management of data heterogeneity caused by system differences in Federated Learning environments.

## Dataset Overview
The HeteroSwitch dataset facilitates research on system-induced data heterogeneity in Federated Learning. It comprises diverse data collected across multiple device types.

To isolate and examine the impact of system-induced data heterogeneity on FL, we create a custom dataset by using a total of nine smartphones: GalaxyS22, GalaxyS9, GalaxyS6, VELVET, G7,  G4,  Pixel5, Pixel2, Nexus5X

Each device is fixed with tripod, and used to capture images displayed on a monitor in a dark room — to isolate the impact of system-induced data heterogeneity and to prevent a potential introduction of the other types of feature distribution skew, we controlled other external factors (e.g., lighting, position, and object being photographed) that may affect the captured images

For the images, we use 12 non-overlapping [ImageNet (Deng et al., 2009)](https://www.image-net.org/) classes from 12 higher-level categories for the images displayed: Chihuahua, Altar, Cock, Abaya, Ambulance, Loggerhead, Timber Wolf, Tiger Beetle, Accordion, French Loaf, Barber Chair, and Orangutan.


### Download Links
Access the dataset through Kaggle at the following URLs:
- [GalaxyS22](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-galaxys22)
- [GalaxyS9](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-galaxys9)
- [GalaxyS6, Nexus5X](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-nexus5x-galaxys6)
- [VELVET](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-velvet)
- [G7](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-g7)
- [G4](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-g4)
- [Pixel 5](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-pixel5)
- [Pixel 2](https://www.kaggle.com/datasets/kimgyudong/heteroswitch-pixel2)

### Citation
Please cite our work using the following Bibtex entry:
```bibtex
@article{kim2024heteroswitch,
  title={HeteroSwitch: Characterizing and Taming System-Induced Data Heterogeneity in Federated Learning},
  author={Kim, Gyudong and Ghasemi, Mehdi and Heidari, Soroush and Kim, Seungryong and Kim, Young Geun and Vrudhula, Sarma and Wu, Carole-Jean},
  journal={arXiv preprint arXiv:2403.04207},
  year={2024}
}
```

We encourage researchers and practitioners to utilize this dataset to explore and address challenges in Federated Learning due to data heterogeneity across devices.
