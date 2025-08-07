# Speaker Identification in Emotional and Neutral Speech

This repository contains the implementation of the method proposed in our paper (currently under review), which addresses speaker identification across both neutral and emotionally expressive speech conditions. The approach combines convolutional and recurrent neural networks for effective modeling of spectro-temporal speech features.

## 📄 Description

- Two main experiments are conducted:
  - **Neutral Speech Identification** using datasets like VCTK, Aishell-1, and THUYG-20.
  - **Emotional Speech Identification** using RAVDESS, EMO-DB, and CREMA-D.

- Evaluation includes:
  - Closed-set speaker identification across varying conditions
  - Performance comparisons with existing models
  - Analysis of the impact of data augmentation on emotional robustness

## 📁 Files

| File | Description |
|------|-------------|
| `identification_aishell.ipynb` | Training and evaluation on neutral speech dataset |
| `speaker_identification_ravdess.ipynb` | Training and evaluation on emotional speech dataset |

## 📊 Datasets Used

- [VCTK Corpus](https://datashare.ed.ac.uk/handle/10283/3443)
- [AISHELL-1](https://openslr.org/33/)
- [THUYG-20](https://openslr.org/22/)
- [RAVDESS](http://zenodo.org/records/1188976)
- [EMO-DB](https://zenodo.org/records/7447302)
- [CREMA-D](https://www.kaggle.com/datasets/ejlok1/cremad)

All datasets are publicly available.

## 🚀 Getting Started

You can run each notebook independently in Jupyter.  
All required dependencies are standard: `TensorFlow`, `Librosa`, `NumPy`, `Matplotlib`, etc.

## 🔒 License

This work is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) License.  
Feel free to reuse for academic or research purposes with attribution. Commercial use is not permitted.

## 📌 Citation

If you use this code or findings in your research, please consider citing our work (paper currently under review). A citation entry will be added once it is published.

---

