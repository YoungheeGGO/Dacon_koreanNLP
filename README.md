I participated in a competition about Korean NLP sponsored by DACON.
If you want to see the detail please click [here!](https://dacon.io/competitions/official/235875/overview/description)
But it is writen in Korean.

**Detail the Competition in English**</br>
The pairwise sentence is consist of premise and hypothesis.
The goal of that competition is hypothesis is discriminated to Entailment, Contradiction, or Neutral by referring to the premise sentence.

# What I felt.
- This is my first time using `hugging face`.
- I didn't have an interest in NLP, but I think the "transfer learning" method is a cool idea.
- The importance of EDA was lower than in other competitions because of no numeric data.
- It competes for model accuracy only!
- We didn't have a server, So We hope the colab supporting GPU is our only hope.
- Free colab returned memory error on baseline code. So I purchased colab pro. And I extended google driver memory to 200GB.
- In colab Pro, We can run the baseline code, but that was all. The model for increasing accuracy (like xlm-RoBERT) couldn't run. It was impossible also GPU,TPU, higher RAM environments.
- We were very disappointed because we want to use other models like HanBert based on Linux or stacking on the other Bert models.
- I wish there is more research about a model that takes low memory and high accuracy.


# What I learned
- For higher prediction, deep learning models can ensemble together -> How about staking? (If I would have an opportunity to use a server or supercomputer, I will try this method.)
- I learned transfer learning based on the BERT model -> koBert, alBert, roBert, xlmBert and so on.

