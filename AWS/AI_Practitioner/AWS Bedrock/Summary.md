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
