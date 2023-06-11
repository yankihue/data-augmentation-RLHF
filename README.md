# data-augmentation-RLHF

This project aims to demonstrate the capabilities of generative LLMs like GPT in fields of data augmentation and reinforcement learning.

The steps to reproduce the results are as follows:

- Start by fine-tuning base GPT-2 to generate positive tweets using [Transformer Reinforcement Learning](https://github.com/lvwerra/trl). [Step 1:](https://github.com/yankihue/data-augmentation-RLHF/blob/main/fine-tune-llm/gpt2-tr-uncontrolled-sentiment-tweets.ipynb) 
- Using this fine-tuned model, generate positive tweets. [Step 2:]() 
- Using an initial sentiment analysis dataset, augment the data by adding these generated positive tweets and then train a model using both the initial and augmented datasets to observe the effects of data augmentation. [Step 3:](https://github.com/yankihue/data-augmentation-RLHF/blob/main/data_augmentation_comparisons/generative_data/sentiment_data/generate_positive_tweets.ipynb) 

You can apply these steps to text classification tasks(economy-labeled news headlines generation) and non-toxic comments generation(detox fine-tuning).

# Reinforcement Learning From Human Feedback

This project also includes all the steps required to gather human feedback using a Discord bot, use this dataset to train a reward model that aligns with these preferences, and then utilize this reward model to fine-tune a LLM. We then use the LLM generatively and use it for data augmentation, and compare the results with using a pre-trained sentiment analysis model as opposed to this human feedback reward model. [The steps can be found here.](https://github.com/yankihue/data-augmentation-RLHF/tree/main/reward%20modeling)

# Results
