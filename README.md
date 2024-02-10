# genAI

![download](https://github.com/mrvinayakjha/genAI/assets/100670889/58b4f3aa-74a5-41e0-b298-dda9bc79f806)


## Introduction to Generative AI Course

Course Objective:
- Generative AI Use cases
- Large Language model(LLMs)
- OpenAI indepth discusssion
- Understanding indepth langchain 
- Vector database
- Llama Index
- Open Source LLM Models
- End-to-End Project (building pipelines)

## DAY-0 Introduction to Generative AI

- Before Going further in Generative AI lets revisit the DeepLearning for more understanding:
  
1. ANN (Artificial Neural network): working with Numerical/Categorical/Structured data -> which solves problems related to Clasification and Regression
2. CNN(Colvulution Neural Network): Feature Extraction -> Pulling -> Flatten the Layer (Colvulution) + ANN
3. RNN(): Sequence Related Data -> Feedback Loop
4. Reinforcement Learning:
5. GAN(Generative Adversial Network)
  
- ### What is Generative AI?
GenAI generate a new Data, based on Training sample. Generative Model can generate image, text, Audio, Videos, etc Data As output.GenAI is a subset of DeepLearning and Generative Models are trained on huge amount of data. While training the Generative Model We don't need to provide a label data., so it is not possible when we have a huge amount of data, so, its just try to see the relationship between the distribution of the data.


## Generative AI is the superset of:

1. Generative Image Model
2. Generative Language Model


## Generative Language Model

LLMs Models are used for:
   TEXT TO IMAGE GENERATION
   TEXT TO TEXT GENERATION
   IMAGE TO IMAGE GENERATION
   IMAGE TO TEXT GENERATION
   
## Generative Image Model 

1. GAN (Highly Used in 2018,19,20)
2. Now LLMs are highly used in Text to Image Generation

## Generative AI Timeline:

- The journey of Generative AI starts with RNN
1. RNN : Here we were using the concept of Time Stamp.
    Limitation: Short Term Memory Dependency resulting in we cannot retain the longeer sentencces using thhis RNN
2. LSTM : Short - Long term Memory Dependencies. Here we were using the concept of Shell State & Time Stamp.Here we have 3 Gate - 1. Forget Gate 2. Inpuyt Gate 3. Output Gate
3. GRU : Introduced in 2014, Took inspiration from LSTM. Here in GRU there is no concept of Shell State Everything is present Under Hidden state.

  ### By using above Architecture we are going to process a Sequence Data(Sequence to Sequence Mapping)
  But there was restriction with sequence to sequence mapping i.e. Fixed Length Of Input and Output
  read this research paper for more: [sequence to sequence model neural network research paper.pdf](https://github.com/mrvinayakjha/genAI/files/14228905/sequence.to.sequence.model.neural.network.research.paper.pdf)


4. Encoder & Decoder Segment :
   Encoder-Decoder, first proposed by Cho et al. (2014b), basically consists of 2 parts, the encoder and the decoder. Encoder codes the sequence of input sentence into dense vector representa- tion, and then decoder takes in the encoded sen- tence and decode the representation into another
sequences of words. They are trained to maximize the conditional probability of the output sentence, given the input sentence.
RNN is necessary when we need to maintain the word order in a sentence. This is not handled by bags of words model or other statistical models. In addition to input, xi and output yˆi, we also have a state vector, ai, which is initialized with vectors of zeros.

5. Attention All You Need by google : In this Encoder Decoder was there but They were not using RNN, LSTM, GRU. It uses TRANSFORMER as Base Model.
   Research Paper : [attention all you need reserch paper.pdf](https://github.com/mrvinayakjha/genAI/files/14228904/attention.all.you.need.reserch.paper.pdf)
   [MachineTranslationwithAttention.pdf](https://github.com/mrvinayakjha/genAI/files/14228972/MachineTranslationwithAttention.pdf)














