**Amazon Bedrock :- **
  - Build Gen AI application on AWS

**Foundational Model :- **

 - Hyper Parameters
     - Epochs :- The total no of iterations of all training data in one cycle for traning the model.
     - Batch Size :- The number of samples processed  before model parameters are updated.
     - Learning rate :- The rate at whch model parameters are updated after each batch of traning data.
     - Learning rate warmup steps :- Number of iterations oer which learning rate is gradually increased to the initial         rate specified.  

**Amazon Bedrock - Fine-Tuning a Model**

   - Fine tuning will change the weights of the base Foundational Model.
     Fine Tuning
       - Instruction based
           - Further trained on a particular field or area of knowledge
           - uses **labeled Example**  that are **prompt-response pairs**
       - Continued Pre-traning
           - Provide unlabeled data to continue training of the Foundational Model.
           - Also called Domain adaptation fine tuning to make a model expert in specific domain.
**Single-Turn Messaging** :-
- Part of instruction based fine-tuning.
**Multi-Turn Messaging**
- Instruction based fine tuning for a conversation
- chatbot = Multi-turn environment
- alternate between "user" and "assistant" roles.

Transfer Learnng vs Fine tuning
----------------
Feature	|Transfer Learning	| Fine-Tuning
-------  ------------------   ------------
Pre-Trained Model Layers|	Mostly frozen|	Some layers updated
New Layers Added?	|Yes|	Not always
Training Effort	|Less	|More
Data Requirement|	Small	|Large
Best When	| New task is similar to the original task|	New task is different from the original task
Risk|	Might not adapt well to new tasks	|Can lead to overfitting if not done properly

