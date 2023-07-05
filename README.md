# Multi-label Video Game Genre Text Classification: Multi-Label Video Game Genre Text Classification Using DistilBERT with Focal Loss Function

## 📌 Abstract
>Video games are getting more popular than ever, with their demands and technologies increasing every day. This continued rise also mirrors its growing size, which will become a daunting task for classification. Genres are typically used to classify video games, which can be quite challenging given their extensive and dynamic nature. Furthermore, video games are also not limited to a single genre; they could belong to multiple genres as well. Because of these reasons, there is now a need for a multi-label genre text classification task for video games. This study addressed the need through natural language processing and fine-tuning a DistilBERT with Focal Loss function for handling data imbalance. Experimental results show that the fine-tuned DistilBERT model with Focal Foss function was able to classify video games reasonably well, achieving micro-average F1 and average precision scores of 0.69 and 0.77, respectively. This performance, however, is only marginally better than that obtained using the loss function usually used in multi-label classification problems. Ultimately, the resulting model serves as a start for video game genre multi-label classification studies that could be beneficial for future research and the gaming industry.  

**Keywords**: video games, genre classification, multi-label classification, text classification, natural language processing

## 📌 Source Code
The code consisted of three parts:  
1. **Data Collection** - Iteration collection using IGDB.com with a wrapper
2. **Data Preprocessing + EDA** - Sanitization and Reduction of data with Exploratory Data Analysis
3. **Model Finetuning, Testing, Evaluation** - DistilBERT model is finetuned, tested, and evaluated with BCE (default loss function) and FL

## 📌 Source Code
- [GitHub of the Study](https://github.com/melzar-jan-chico-UP/sp_multilabel_vggtc.git)
- [My Uploaded Dataset on Kaggle](https://www.kaggle.com/datasets/melzarjanchico/multilabel-video-game-dataset-v2)