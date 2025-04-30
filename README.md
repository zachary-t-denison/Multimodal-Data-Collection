# Multimodal Data Collection — Robot-Assisted Surgery  
> *DSA Fall 2025 – Peg Transfer (Raven vs TrakStar)*  

Hello Professor / PhD 👋  

Before you run any code, **add the raw-data folder as a Drive shortcut**:

1. Open <https://drive.google.com/drive/folders/15xZ_yFUGSWpyW_fx_ec6IfNK-I2PiuMm?usp=sharing>  
2. Click **Organize → Add shortcut → My Drive**

---

## Quick start (Google Colab)

| action | link |
|--------|------|
| Launch notebook | [link text](https://colab.research.google.com/drive/1ik8DFZMTrygnund0L0-lzas5qSziNuvZ?usp=sharing) |
| Raven Plots | [link text](https://drive.google.com/file/d/1-o8lJc-GdjUIjM4p6rQP4WA8JAq5EOWk/view?usp=sharing) |
| TrakStar Plots | [link text](https://drive.google.com/file/d/10EF0w2BwUizMmkf1cNpyL8d5Ca9DQI6p/view?usp=sharing) |
| View variable-match table | [link text](https://TABLE_URL) |
| Overlay GIF examples | [link text](https://GIF_URL) |

> *GPU/TPU availability on Colab fluctuates; evenings (~9 pm) tend to give the best hardware.*

---

## Local setup

```bash
# 1 – clone our repo and pull the large files via Git LFS
git clone https://github.com/YourOrg/peg-transfer.git
cd peg-transfer
git lfs install
git lfs pull

# 2 – create env
conda env create -f environment.yml          # or: pip install -r requirements.txt
conda activate raven-trakstar
