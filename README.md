# Artificial Neural Netweorks and Deep Learning Competition
In this repository there can be found the *Jupyter Notebooks* used by me and my collegues to participate to the competition of Politecnico di Milano course *Artificial Neural Networks and Deep Learning* (2021/2022).

The competition was based on two different challenges:
- Image Classification
- Time Series Forecasting

## 1. Image Classification
**Goal:** build a multiclass classifier to correclty classify images of leaves according to their plant specie
![Schermata 2022-07-19 alle 11 57 49](https://user-images.githubusercontent.com/79702744/179723634-5e1d3f8b-91c8-4f64-a13f-ad6609ca26a8.png)

**Dataset Deitails**: 
- Image size: 256x256
- Color space: RGB
- File Format: JPG


| Class number | Class name | Training images |
| ------------ | ---------- | ---------------- |
| 0 | Apple | 988 |
| 1 | Blueberry | 467 |
| 2 | Cherry | 583 |
| 3 | Corn | 1206 |
| 4 | Grape | 1458 |
| 5 | Orange | 1748 |
| 6 | Peach | 977 |
| 7 | Pepper | 765 |
| 8 | Potato | 716 |
| 9 | Raspberry | 264 |
| 10 | Soybean | 1616 |
| 11 | Squash | 574 |
| 12 | Strawberry | 673 |
| 13 | Tomato | 5693 |

**Evaluation**: ![CodeCogsEqn (1)](https://user-images.githubusercontent.com/79702744/179723321-90a118bd-0e68-4827-9e0f-6d51a4c4d13e.svg) where N is the ottal number of images in the test set

## 2. Time Series Forecasting
**Goal**: design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the future

**Dataset Detials**: only the training set has been provided, the models were evaluated with a hidden test on the challange's platform
We provide a training multivariate time series with the following characteristics
- Length of the time series (= number of samples in the training set):   68528
- Number of features: 7
- Name of the features: 'Sponginess', 'Wonder level', 'Crunchiness', 'Loudness on impact', 'Meme creativity', 'Soap slipperiness', 'Hype root'
- The provided time series has a uniform sampling rate

**Evaluation**: RMSE

