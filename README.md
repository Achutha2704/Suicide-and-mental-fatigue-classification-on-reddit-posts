# Suicide-and-mental-fatigue-classification-on-reddit-posts

We created our own dataset using Reddit APIs and webcrawling using PRAW on multiple subreddits and search queries focusing on happy and sad content.
Data preprocessing: extracted datasets is stripped from unnecessary characters and certain emojis. Then, the dataset is tokenized and combined.
Fine-tuning RoBERTa: We imported RoBERTa from huggingface transformers and fine-tuned it. The model is trained with a small labelled dataset available which does not contain any additional features. We try with different classification heads (XGB and simple NN with a linear output).  
Transfer learning: We use the fine-tuned model to label the dataset created. 

![Screenshot 2024-05-28 160813](https://github.com/Achutha2704/Suicide-and-mental-fatigue-classification-on-reddit-posts/assets/113625925/bf4d5261-ab65-44b7-a3e2-d62943ccff22)

![Screenshot 2024-05-28 160843](https://github.com/Achutha2704/Suicide-and-mental-fatigue-classification-on-reddit-posts/assets/113625925/5d5e2164-952a-4380-b27b-70398e43dc2f)

