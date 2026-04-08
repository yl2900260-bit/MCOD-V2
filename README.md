# MCOD-V2: A Challenging Text-Guided Multispectral Benchmark for Multi-Camouflaged Object Detection

This is the official repository for the **MCOD-V2** dataset.

---

## 📥 Data Download

We provide two sources for downloading the dataset and supplementary materials. Please choose the appropriate link based on your requirements for multispectral data.

| Source | Content | Access Link |
| :--- | :--- | :--- |
| **Baidu Netdisk** | **Full Dataset** (Includes Multispectral Images) & Supplementary Materials | [Download](https://pan.baidu.com/s/1drOvr8SGhNFv43QquroBlQ?pwd=kd2w) (Code: `kd2w`) |
| **Google Drive** | **Lite Dataset** (Includes everything **EXCEPT** Multispectral Images) | [Download](https://drive.google.com/file/d/1bfC-EJ_MW512fYQLkNboFVl6kTva_Ey0/view?usp=sharing) |

> [!IMPORTANT]
> **Size Notice:** Due to the large file size of the multispectral images (`.mat` files), the Google Drive link only contains images and annotations. For the complete dataset including multispectral data, please use the Baidu Netdisk link.

---

## 📂 Dataset Structure

```text
MCODV2/
├── TrainDataset/
│   ├── Train_mat/     # Multispectral data (Baidu Netdisk only)
│   ├── Imgs/          # Pcolor images
│   ├── GT/            # Ground truth
│   └── train_txt      # Text annotation
└── TestDataset/
    ├── Test_mat/      # Multispectral data (Baidu Netdisk only)
    ├── Imgs/          # Pcolor images
    ├── GT/            # Ground truth
    └── test_txt       # Text annotation
