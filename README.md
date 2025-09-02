# Particle Dataset (particle_dataset)

## Overview

This DeepTrackAI repository contains two short videos of an optically trapped microscopic particle undergoing Brownian motion in the optical potential. The dataset was published in [Helgadottir et al., Optica, 2019](https://doi.org/10.1364/OPTICA.6.000506). 

One video is acquired with **low noise** (`low_noise.avi`), and the other with **high noise** (`high_noise.avi`). In both cases, the particle jiggles around the center of the frame due to thermal motion.

### Summary
- **Number of videos**: 2 (`low_noise.avi`, `high_noise.avi`)  
- **Frames per video**: 100  
- **Image size**: 120 × 120 pixels  
- **Video format**: 8-bit RGB AVI  

---

## Original Source

- **Title:** Digital video microscopy enhanced by deep learning  
- **Authors:** Saga Helgadottir, Aykut Argun, Giovanni Volpe  
- **Journal:** Optica, 6(4): 506–513 (2019)  
- **DOI:** [10.1364/OPTICA.6.000506](https://doi.org/10.1364/OPTICA.6.000506)

If you use this dataset in your research, please follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/particle_dataset  
├── low_noise.avi     # Low-noise video of trapped particle (100 frames)  
└── high_noise.avi    # High-noise video of trapped particle (100 frames)
```

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/particle_dataset
cd particle_dataset
```

---

## Attribution

### Cite the original paper:
Helgadottir S, Argun A, Volpe G. *Digital video microscopy enhanced by deep learning.* Optica, 6(4): 506–513 (2019). [https://doi.org/10.1364/OPTICA.6.000506](https://doi.org/10.1364/OPTICA.6.000506)

```bibtex
@article{helgadottir2019digital,
  title={Digital video microscopy enhanced by deep learning},
  author={Helgadottir, Saga and Argun, Aykut and Volpe, Giovanni},
  journal={Optica},
  volume={6},
  number={4},
  pages={506--513},
  year={2019},
  publisher={Optica Publishing Group}
}
```

---

## License

This dataset is shared under the **Creative Commons Attribution-Share Alike 3.0** License, following the original licensing terms.
