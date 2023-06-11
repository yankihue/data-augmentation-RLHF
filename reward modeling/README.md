### Reward Modeling

To gather human feedback to train the reward model, [we wrote a Discord bot.](https://github.com/yankihue/reward-model-trainer-discord) 


Order of operations to train reward model:
- Generate initial dataset with mixed choices for humans to rank - [Link to notebook 1](https://github.com/yankihue/data-augmentation-RLHF/blob/main/reward%20modeling/unlabeled%20human%20RLHF%20data%20for%20discord%20bot%20TWEETS.ipynb) and [2](https://github.com/yankihue/data-augmentation-RLHF/blob/main/reward%20modeling/mark_unranked_outputs.ipynb)
- Create human preferences dataset utilizing [RMTD](https://github.com/yankihue/reward-model-trainer-discord) (or use other existing datasets)
- Train reward model from human preferences and push to huggingface hub for later use [Link to notebook](https://github.com/yankihue/data-augmentation-RLHF/blob/main/reward%20modeling/train_sentiment_hf_reward_model.ipynb)
