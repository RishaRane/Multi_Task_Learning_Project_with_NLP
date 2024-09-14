# Multi-Task NLP model using LSTM

- Multi-task learning (MTL) is a machine learning approach where a model is trained simultaneously on multiple related tasks!

Libraries used:
- Pandas, Numpy, Scikit-learn, nltk, tensorflowm seaborn, matplotlib


Following is the architecture of the project:
- [Architecture](https://github.com/user-attachments/assets/597b47c6-33bd-4570-bbf5-894d4346f6b9)

Compontents:

(i) Individual Inputs:
- Multi-Task model accepts input for each task individually.

(ii) Individual Outputs:
- Multi-Task model generates output for each task individually

(iii) Shared Core Layers:
- Multi-Task models functionality is that a sinlge model can do multiple related tasks. To exhibit this functionality the core layers of the model like (Embedding, LSTM, pooling, dropout etc) are shared among all the tasks and are not seperately available for them
