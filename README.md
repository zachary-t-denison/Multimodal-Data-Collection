# Multimodal Data Collection — Robot-Assisted Surgery  
> *DSA Fall 2025 – Peg Transfer (Raven vs TrakStar)*  

Hello Professor / PhD 👋  

Before you run any code, **add the raw-data folder as a Drive shortcut**:

1. Open <https://drive.google.com/drive/folders/1o4cQxVECPM1cNhsV3zzpBtEfMhhzUYH3>  
2. Click **Organize → Add shortcut → My Drive**

---

## Quick start (Google Colab)

| action | link |
|--------|------|
| Launch notebook | [link text](https://colab.research.google.com/drive/1ik8DFZMTrygnund0L0-lzas5qSziNuvZ?usp=sharing) |
| Raven Plots | [link text](https://drive.google.com/drive/folders/1rK6XSf5GtRrvqsq1602jDFVAaLuqJF2n?usp=sharing) |
| TrakStar Plots | [link text](https://drive.google.com/drive/folders/1_Sb23aqhxri4HyQnZ_PIJ3qvyQ1KZDr0?usp=sharing) |
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
