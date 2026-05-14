[![Review Assignment Due Date]
# Fine-tuning LLMs for summarization

In this assignment you will have to fine-tuned pre-trained Large Language Models for the task of **text summarization**. For this task we will use the [**CNN Dailymail dataset**](https://huggingface.co/datasets/abisee/cnn_dailymail). The CNN DailyMail Dataset is an English-language dataset containing just over 300k unique news articles as written by journalists at CNN and the Daily Mail. For each instance, there is a string for the article and a string for the highlights that form a summary of the article. The dataset has 287,113 samples for training, 13,368 for validation adn 11,490 for testing.

The final goal of this assignment is achieve the best performance in this task by fine-tuning a pre-trained model under 1B parameters. You will have to fine-tune at least one encoder-decoder model and one decoder-only model. You can explore different configurations of the models (architecture, model size, sampling strategy, ...), selection and processing of the training dataset (training size, prompting strategies, context length, ...) and the training process (training recipes, optimization hyperparameters, batch size, number of epochs, ...). Furthermore, pick two or three of these factors and perform a detailed analysis of their impact in the final results.   



## NOTE

NotebookVisualizationRun was for the visualization only, TrainingAndAblationNotebook were for the actual training and Ablation of the models. I hit the Kaggle limit multiple times, this is why there had to be two notebooks.
