# DropKey-Augmented Lightweight ViT for Soil Classification

**This repository contains the official implementation for the paper:**  
> **Enhancing Soil Classification with DropKey-Augmented Lightweight Vision Transformers**  
> *Submitted to Journal of Computer Science and Technology (Submission ID: IDJCST-2511-16117)*  
> **Authors**: [Yan ZHANG,Rui-Feng-Li,Lantao-Huang,Feng-Tao-LIU/Team], [Guangxi Key Laboratory of Geotechnical Mechanics an Engineering, Guilin University of Technology, Guilin 541004, China]  
> (https://doi.org/10.6084/m9.figshare.29550056)

📢 **Citation Request**:  
If you use this code or results in your research, please cite our paper:
```bibtex
@article{your2024enhancing,
  title={Enhancing Soil Classification with DropKey-Augmented Lightweight Vision Transformers},
  author={Yan ZHANG,Rui-Feng-Li,Lantao-Huang,Feng-Tao-LIU/Team},
  journal={Submitted to The Visual Computer},
  year={2025},
  note={Submission ID: IDJCST-2511-16117}
}


🚀 Quick Start
1. Environment Setup

# Create conda environment (recommended)
conda create -n soilcls python=3.11
conda activate soilcls

# Install core dependencies
pip install torch==2.4.0 torchvision==0.16.0 torchaudio==2.0.1 --index-url https://download.pytorch.org/whl/cu121

# Install remaining packages
pip install -r requirements.txt
****

2. Prepare Dataset
Download soil images from [https://www.kaggle.com/datasets/prasanshasatpathy/soil-types/https://www.kaggle.com/datasets/jhislainematchouath/soil-types-dataset]
Organize directory structure:
data/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
└── test/
    ├── class1/
    ├── class2/
    └── ...
3.Run Modles:
The base model runs directly :train.ipynb   (you can also use filename.py  Running model with command at terminal:python train.py or python train.ipynb )
Full model run :Aug+DropKey.ipynb

📊 Key Features
Hybrid Augmentation: Adaptive MixUp + CutMix strategies
Dynamic DropKey: Sparse attention for efficient computation

❓ Contact
For technical inquiries, please contact:

[RuiFeng Li] - [1971777601@qq.com]
