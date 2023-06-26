#  KoELECTRA Sentiment Analysis Trainer

This repository contains a trainer for sentiment analysis using KoELECTRA (Efficiently Learning an Encoder that Classifies Token Replacements Accurately). The trainer allows you to train a KoELECTRA model for sentiment classification and evaluate its performance on validation data. It also supports early stopping based on the F1-micro score.

## Requirements

- Python 3.9
- torch==2.0.1
- transformers==4.30.0
- pandas==2.0.2
- tqdm==4.65.0
- scikit-learn==1.2.2

## Usage

Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Reference
Google-research/electra
   
   ```
   https://github.com/google-research/electra
   ```
   ```
   https://openreview.net/pdf?id=r1xMH1BtvB
   ```

beomi/KcELECTRA-babs from huggingface 

   ```
   https://huggingface.co/beomi/KcELECTRA-base
   ```