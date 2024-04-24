Dynamic Weighting Translation Transfer Learning (DTTL) for Imbalanced Medical Image Classification

This repository contains the implementation of the Dynamic Weighting Translation Transfer Learning (DTTL) as described in our paper submitted to the Entropy journal. DTTL addresses key challenges in medical image diagnosis using deep learning, including domain shift and class imbalance, via a novel transfer learning approach.

## Overview
The DTTL framework comprises three main modules:
- **Cross-domain Discriminability Adaptation (CDA)**: Enhances feature learning across domains using a synthetic discriminability loss.
- **Dynamic Domain Translation (DDT)**: Implements a dynamic translation process for balancing classes between domains using synthesized images.
- **Balanced Target Learning (BTL)**: Conducts supervised learning on a balanced target set to derive the diagnostic model.

## Installation
To set up a local copy of the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yucl2019/DTTL
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the DTTL model on your data, follow these steps:

1. Prepare your dataset according to the guidelines provided in the `data/` directory.
2. Modify the configuration settings in `config.py` as needed.
3. Run the main script:
   ```bash
   python main.py
   ```

## Dependencies
- Python 3.8+
- PyTorch 1.7+
- NumPy
- PIL
- See `requirements.txt` for more details.

## Contributing
We welcome contributions to improve the DTTL methodology. Please feel free to fork this repository, make changes, and submit pull requests.

## Citation
If you find this work useful for your research, please cite our paper:

```
@article{yourname2024dttl,
  title={Dynamic Weighting Translation Transfer Learning for Imbalanced Medical Image Classification},
  author={Your Name and Co-authors},
  journal={Entropy},
  year={2024},
  url={https://github.com/yucl2019/DTTL}
}
```

## Contact
For questions and feedback, please contact [Your Email].

Thank you for visiting our project!
```

请根据实际情况替换占位符（如您的名字、联络邮箱等）以及调整各部分内容以符合您的项目细节。
