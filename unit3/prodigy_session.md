## Session 3
The third session will focus on Prodigy, which is an annotation tool used to train and evaluate spaCy language models. Building on knowledge from the second session, participants will learn how to use Prodigy to quickly train new categories and entities on existing language models. Prodigy utilizes a method called active learning in which human input and automated learning are both used to update the model. Prodigy sorts the model's uncertain results and strategically asks for user input. These annotations are then used to update the model on new categories or to improve accuracy with a specific task. In this session, participants will learn how to train custom language categories and entities using Prodigy.
Participants will leave the session with a clear end-to-end workflow from an initial text, to training, to the application of trained models. Building on Unit II, we will use the new model to automatically update a TEI document with the new categories and data.


- Prodigy installation 
- Quick and simple example, train a new category, train a new entity with an existing model.
- Paths in the [Prodigy workflow](https://github.com/apjanco/spaCy_DH2019_workshop/raw/master/unit3/prodigy_workflow.jpeg)
  - Improve existing pre-trained model 
  - Add new entity types to existing model 
  - Train a new model from scratch 
  - Collect more annotations 
  - Write a patterns JSONL file 

- ner.manual 
- ner.teach
- ner-batch-train
- ner.train-curve 
