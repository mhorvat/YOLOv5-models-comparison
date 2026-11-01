# YOLOv5-models-comparison

This repository contains the complete dataset created for the research presented in the scientific paper "**A comparative study of YOLOv5 models performance for image localization and classification**" published at the 33rd Central European Conference on Information and Intelligent Systems (CECIIS 2022), held in Dubrovnik, Croatia.

Conference website: <a href="https://ceciis.foi.hr/" target="_new" rel="noopener">https://ceciis.foi.hr/</a>

The paper can be accessed on <a href="https://archive.ceciis.foi.hr/public/conferences/2022/Proceedings/IS/IS4.pdf" target="_new" rel="noopener">this link</a> or on <a href="https://www.researchgate.net/publication/363824867_A_comparative_study_of_YOLOv5_models_performance_for_image_localization_and_classification" target="_new" rel="noopener">this link</a>.

**The created dataset and the codebase are available for research and non-commercial use only.**

If you are using any part of this dataset for your own work or research, please use the following citation:

M. Horvat, L. Jelečević, and G. Gledec, "A comparative study of YOLOv5 models performance for image localization and classification," in *Proc. Central Eur. Conf. Inf. Intell. Syst. (CECIIS)*, Varaždin, Croatia: Faculty of Organization and Informatics, 2022, pp. 349–356.

---

### BibTeX Entry

```bibtex
@inproceedings{horvat2022comparative,
  author    = {Horvat, Marko and Jele{\v{c}}evi{\'c}, L. and Gledec, Gordan},
  title     = {A Comparative Study of {YOLOv5} Models Performance for Image Localization and Classification},
  booktitle = {Proceedings of the Central European Conference on Information and Intelligent Systems (CECIIS)},
  address   = {Vara{\v{z}}din, Croatia},
  publisher = {Faculty of Organization and Informatics},
  pages     = {349--356},
  year      = {2022}
}

```

---

### Training different YOLOv5 models on 'Face Mask Detection' dataset for comparison.

#### Pretrained weights
Pretrained weights for each model can be found in `weights` directory.

#### Scores
Detailed results for each model are located in `results` directory.

#### Jupyter notebook
Jupyter notebook is written with [Google Colab](https://colab.research.google.com/) in mind, but can be used with [Kaggle](https://www.kaggle.com/) for bigger datasets (33h GPU usage time limit). Every Kaggle batch session will end in an irrelevant error caused by differences in working directory structures between Kaggle and Collab. Results still can be downloaded.
Notebook utilizes [ultralytics'](https://github.com/ultralytics/yolov5) YOLOv5 library.

##### Usage
Upload your dataset to [Roboflow](https://roboflow.com/) and export it in YOLOv5 PyTorch format with _show download code_ enabled. Replace `#API#` and `#PROJECTNAME#` and you're ready to go.

#### Dataset
_Face Mask Detection_ dataset used for training is available [here](https://www.kaggle.com/andrewmvd/face-mask-detection). Dataset consists of 1677 images. 

![Prediction example](https://raw.githubusercontent.com/thelcrysis/YOLOv5-models-comparison/main/results/yolov5x/val_batch1_labels.jpg )
