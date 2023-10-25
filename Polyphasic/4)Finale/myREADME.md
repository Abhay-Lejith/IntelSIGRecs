# My Machine Learning System

- I have used the same q/a model as in the second notebook I submitted in task 2C (the one finetuned on newsQA). Could not attach it in resources due to its large size.
- The translation model also could not be added to resources file because of its large size. I have attached the notebook in resources which was used to generate the pickled tokenizers and model.
- The context and question can be modified in the notebook before it is run. The answer is returned at the end of the notebook in both french and english.

### Some things I could've changed:

- Should have used the q/a model from the third notebook which was better but did not have time.
- Reduced learning rate on the english to french translation model while training. The validation loss increased rather than decrease. It has overfit. Did not have time to train again.
- As a result the quality of the translated answers are rather poor.