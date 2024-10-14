# project 1: Logistic Regression
you will be implementing logistic regression for sentiment analysis on tweets. Given a tweet, you will decide if it has a positive sentiment or a negative one. Specifically you will:

Learn how to extract features for logistic regression given some text
## Implement logistic regression from scratch
Apply logistic regression on a natural language processing task
Test using your logistic regression
Perform error analysis

![image](https://github.com/user-attachments/assets/5234a571-a5ff-4318-b78a-b709533c2c0f)

![image](https://github.com/user-attachments/assets/1e831678-a2a5-4002-bc5c-1b66f1094248)

===================================================================================================================
# project 2: Autocorrect
You use autocorrect every day on your cell phone and computer. you will explore what really goes on behind the scenes.

prosedure step by step:

- Get a word count given a corpus
- Get a word probability in the corpus
- Manipulate strings
- Filter strings
- Implement Minimum edit distance to compare strings and to help find the optimal path for the edits.
- Understand how dynamic programming works
Similar systems are used everywhere.

For example, if you type in the word "I am lerningg", chances are very high that you meant to write "learning", as shown in Figure 1.

![image](https://github.com/user-attachments/assets/73ea5ef5-d8e0-4831-9f03-bbd9ef771f09)

====================================================================================================================

# project 3: Parts-of-Speech Tagging (POS)

Parts-of-Speech Tagging (POS)

Distinguishing the parts-of-speech of a word in a sentence will help you better understand the meaning of a sentence. This would be critically important in search queries. Identifying the proper noun, the organization, the stock symbol, or anything similar would greatly improve everything ranging from speech recognition to search. By completing this assignment, you will:

- Learn how parts-of-speech tagging works
- Compute the transition matrix A in a Hidden Markov Model
- Compute the emission matrix B in a Hidden Markov Model
- Compute the Viterbi algorithm
- Compute the accuracy of your own model

====================================================================================================================
# project 4: Question duplicates using the Siamese Network
A Siamese network is a neural network which uses the same weights while working in tandem on two different input vectors to compute comparable output vectors. The Siamese network you are about to implement looks something like this:

![image](https://github.com/user-attachments/assets/91e7a7ae-e1e6-4916-a51a-516f347d7926)

You get the question, get it vectorized and embedded, run it through an LSTM layer, normalize v1, v2 and and finally get the corresponding cosine similarity for each pair of questions. Because of the implementation of the loss function you will see in the next section, you are not going to have the cosine similarity as output of your Siamese network, but rather v1 and v2. You will add the cosine distance step once you reach the classification step.

====================================================================================================================

# project 5: NMT model with attention

Adding an attention layer to RNN model avoids gradient vanish problem by giving the decoder access to all parts of the input sentence. To illustrate, let's just use a 4-word input sentence as shown below. Remember that a hidden state is produced at each timestep of the encoder (represented by the orange rectangles). These are all passed to the attention layer and each are given a score given the current activation (i.e. hidden state) of the decoder.

![image](https://github.com/user-attachments/assets/9d172e6c-ac34-42df-9d0f-ce5ca2309b14)

![image](https://github.com/user-attachments/assets/32902a35-6de1-4ede-8302-134682ae44fc)

you can think of it as computing scores using queries (Q) and keys (K), followed by a multiplication of values (V) to get a context vector at a particular timestep of the decoder. This context vector is fed to the decoder RNN to get a set of probabilities for the next predicted word.
