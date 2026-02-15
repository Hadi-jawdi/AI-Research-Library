# AGI Papers

| Title | Year | Link 
|-------|------|------|
| Sparks of AGI | 2023 | [Paper-link](https://arxiv.org/abs/2303.12712) |

<h1>My understanding from the paper</h1>
Based on this paper: LLMS should be improved in the following areas to achieve more general intelligence: 
Confidence calibration:models don't know when they are right versus when they are guessing. This leads to hallucinations.


Long-term Memory: The model’s context is very limited, it operates in a stateless fashion and
there is no obvious way to teach the model new facts.

Continual learning:models don't have the ability to update itself, learn new things or adapt itself to the environment. The model can do tasks which was trained for. However, developers can finetune the model, but it causes some problems like overfitting(memorize the training set. Fails to predict un seen data).
Challenges with sensitivity to inputs: Models are sensitive to inputs. In order to get clear, accurate, and more professional response from the model. The user should provide a clear and understandable prompt for model
