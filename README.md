# Climate Prediction Using Temporal Fusion Transformers (TFT)

This project implements a robust climate forecasting pipeline using the **Temporal Fusion Transformer (TFT)** from the Darts time series library. It demonstrates a complete workflow from data preparation to model training, forecasting, and evaluation.

## 📌 Objectives

- Predict future climate indicators such as **temperature** and **humidity**
- Leverage **temporal covariates** and **deep learning** techniques
- Integrate **probabilistic forecasting** and **backtesting** to validate performance

## 🛠️ Tools & Libraries

- [Darts](https://github.com/unit8co/darts) (Time Series Library)
- Pandas, NumPy, Matplotlib
- Google Colab (for cloud-based execution)
- `kagglehub` (for dataset management via Kaggle API)

## 📁 Project Structure

```
├── Climate_prediction.ipynb     # Main notebook
├── requirements.txt             # Required packages
└── data/                        # (Auto-created) Folder for downloaded climate data
```

## ⚙️ Setup Instructions

1. Clone the repository or open the notebook in **Google Colab**.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Authenticate with Kaggle:
   - Upload your `kaggle.json` file
   - Set `KAGGLE_USERNAME` and `KAGGLE_KEY` as secrets in Colab or environment variables locally

4. Run the notebook step-by-step to:
   - Download and preprocess data
   - Train the TFT model
   - Generate forecasts
   - Evaluate results with backtesting

## 📈 Key Features

- **Temporal Fusion Transformer (TFT):** State-of-the-art attention-based model for time series
- **Multi-variable forecasting:** Uses multiple covariates for better accuracy
- **Probabilistic outputs:** Generates confidence intervals for predictions
- **Visualization tools:** Plots actual vs. predicted trends

## 📊 Sample Output

> Plots and forecast metrics (e.g., MAE, RMSE) are automatically generated in the notebook.

## ✅ Status

- [x] End-to-end pipeline
- [x] Forecasting with TFT
- [x] Dataset integration via Kaggle
- [ ] Future work: Hyperparameter tuning and model comparison

## 📄 License

This project is licensed under the MIT License.
