[FLAN T5 large model](https://huggingface.co/google/flan-t5-large) is used to observe the effect of different promptings on the output of large languga models in reasoning tasks. 
[BBH dataset](https://huggingface.co/datasets/lukaemon/bbh/viewer/sports_understanding) is used to evaluate model accuracy in terms of answering yes/n questions. One-shot examples are taken from the train seet while the evaluation is done on the test dataset.
It is worth noting that the model input and output are both processed to evalute the model and the full code to pre and post processing is also available in the notebook.
The procedure taken for evaluation and prompting techniques used are similar to ones mentioned in [this paper](https://arxiv.org/abs/2210.11416). 
