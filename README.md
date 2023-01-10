# Final Project

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

## Download Dataset

### [download the dataset](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/data)


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
├── reproduce-model
└── requirements.txt
```

## Requirements


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
4. Find reproduce models in `reproduce-model`


## Inference

1. Open 109550050_Final_inference.ipynb
2. Ensure you are in the virtual environment
3. Click run all.

## Results

Predict result will be stored in `109550050.csv`

Our model achieves the following performance on :

### [Tabular Playground Series - Aug 2022](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)

| Private Score | Public Score |
|-------------- | ------------ |
|    0.59056    |    0.58563   |




## Contributing

- [TPSAUG22 EDA which makes sense ⭐️⭐️⭐️⭐️⭐️](https://www.kaggle.com/code/ambrosm/tpsaug22-eda-which-makes-sense)
- [GroupKFold isn't enough](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/discussion/341896)
- [Feature Scaling](https://ithelp.ithome.com.tw/articles/10237985?sc=rss.iron)