# Final Project

## For Colab

Modify `basedir` and `save_path` to the correct path

## Clone the repo

SSH:
```SSH
git clone git@github.com:BaBa0525/ML-Final-Project.git
```
HTTPS:
```HTTPS
git clone https://github.com/BaBa0525/ML-Final-Project.git
```

Enter the repo:

```cd
cd ML-Final-Project
```

## Requirements

### [Download the dataset](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/data)

### [Download Pretrained Model (For inference)](https://drive.google.com/drive/folders/1w23bvOf5d6-CEmAcRDuGHDZ7cowxh8Bi?usp=share_link)

File structure:

```
.
├── 109550050_Final_inference.ipynb
├── 109550050_Final_train.ipynb
├── README.md
├── dataset
│   ├── sample_submission.csv
│   ├── test.csv
│   └── train.csv
├── model
│   ├── model_0.joblib
│   ├── model_1.joblib
│   ├── model_2.joblib
│   ├── model_3.joblib
│   └── model_4.joblib
└── requirements.txt
```

To create virtual environment:

```venv
python3 -m venv .venv
source ./.venv/bin/activate
```

To install requirements:

```setup
pip install -r requirements.txt
```

## Training

1. Open 109550050_Final_train.ipynb
2. Ensure you are in the virtual environment
3. Click run all.
4. Find reproduce models in `model`
5. Predict result will be stored in `109550050.csv`


## Inference

1. Open 109550050_Final_inference.ipynb
2. Ensure you are in the virtual environment
3. Ensure the pretrained models in `./model`
4. Click run all.
5. Predict result will be stored in `109550050.csv`

## Results

Our model achieves the following performance on :

### [Tabular Playground Series - Aug 2022](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)

| Private Score | Public Score |
|-------------- | ------------ |
|    0.59056    |    0.58563   |




## Contributing

- [TPSAUG22 EDA which makes sense ⭐️⭐️⭐️⭐️⭐️](https://www.kaggle.com/code/ambrosm/tpsaug22-eda-which-makes-sense)
- [GroupKFold isn't enough](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/discussion/341896)
- [Feature Scaling](https://ithelp.ithome.com.tw/articles/10237985?sc=rss.iron)