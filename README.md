# Fine-tuning BERT for Sentiment Analysis of Mental Health Dataset

## Abstract
In this paper, we explore the application of a fine-tuned BERT-based classifier to predict mental health conditions from user statements. The classifier was trained on an aggregated Kaggle mental health dataset, achieving an overall accuracy of 83\% and a weighted F1-score of 0.83, outperforming traditional baseline models like Linear SVM (accuracy: 77.89\%, F1-score: 0.78). BERT demonstrated superior handling of minority classes, with significant improvements in F1-scores for "Bipolar" (0.89 vs. 0.61) and "Personality Disorder" (0.77 vs. 0.68) compared to SVM. However, challenges arose in accurately classifying overlapping categories such as "Stress" and "Depression" and in identifying "Suicidal" text, where BERT underperformed relative to simpler models. These findings emphasize the importance of addressing class imbalances and refining loss functions for complex datasets. This paper highlights the potential of pre-trained language models for use in mental health detection and support, offering insights into their strengths and limitations.
## Files

mental_health_bert.py is the notebook where we ran our experiments, it includes calls for EDA, model finetuning, inference, and error analysis.
See Finetuning_BERT_for_mental_health_dataset.pdf for the full experimentation and results. 
