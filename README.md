## 🔋 IEEE Battery Temperature Prediction Using Deep Learning and Transformers

<img width="645" height="878" alt="Image" src="https://github.com/user-attachments/assets/0b6c0730-e597-423e-b7e9-1e20c3ce9375" />

This repository contains the implementation and analysis of deep learning models for accurate **temperature prediction of Panasonic 18650PF Lithium-Ion cells**, based on **Electrochemical Impedance Spectroscopy (EIS)** data collected at varying ambient temperatures. This work was made **by me** and was also published in **IEEE** with the best paper award as **first author**. 

## ⚠️ Important Notes: Kindly Read and Consent Before Proceeding

**Kindly do not misuse it's contents or mention contents of paper without proper consent!! The other two authors are corresponding authors whose work was to only co-ordinate in pulishing. The Development and Complete Writings of the paper belongs to me hence with due request only refer to me if needing more details about the paper!! I'm glad to be of help hoping you will like the work. Anyone trying to steal or claim credits for work is clearly non-acceptable and may lead to legal issues.**



## 📘 Abstract

Maintaining the **safety**, **longevity**, and **performance** of lithium-ion cells is critical for high-demand applications such as **electric vehicles** and **energy storage systems**. This study explores deep learning techniques—especially **Transformers** and **Recurrent Neural Networks (RNNs)**—to predict battery temperature from EIS data.

The models evaluated include:
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Bidirectional LSTM (Bi-LSTM)
- Minimal Gated Unit (MGU)
- Transformer-based architectures

The study concludes that while **GRU** performs best individually, **ensemble approaches** offer the most efficient trade-off between speed and accuracy.

## 📊 Results

| Model        | MSE    | RMSE   | R² Score |
|--------------|--------|--------|----------|
| LSTM         | 1.4996 | 1.2246 | 0.9943   |
| GRU          | **0.9615** | **0.9806** | **0.9963**   |
| Bi-LSTM      | 1.0734 | 1.0360 | 0.9959   |
| Ensemble     | 1.1535 | 1.0740 | 0.9956   |

> ✅ **GRU** achieves the best performance across all metrics.  
> 🔄 **Ensemble models** still offer a good balance between performance and generalization.  
> 🔍 While **LSTM and Bi-LSTM** perform decently, they trail slightly behind GRU and ensemble methods.

## 🧠 Models & Techniques

- 📈 **Data Source**: Electrochemical Impedance Spectroscopy (EIS)
- 🧠 **Models**:
  - LSTM
  - GRU
  - Bi-LSTM
  - MGU
  - Transformer
- 📏 **Metrics**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
