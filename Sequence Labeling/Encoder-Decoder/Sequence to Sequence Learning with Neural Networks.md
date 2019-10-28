# Title Sequence to Sequence Learning with Neural Networks
+ Referrer: HJ, Level: 10
+ Reasons: One of the first paper about the Encoder-decoder model.
+ Proceedings or Journal: arxiv
+ [PDF Link](https://arxiv.org/pdf/1409.3215.pdf)  
+ [Code (Torch7)](https://github.com/bgshih/crnn) [Code (Pytorch)](https://github.com/meijieru/crnn.pytorch)
+ Organization: Google
+ Authors: Ilya Sutskever, Oriol Vinyals, Quoc V. Le

# Contributions
+ Propose a general end-to-end approach to sequence learning that makes minimal assumptions on the sequence structure.
+ This method uses a multilayered long short-term memory to map the input sequence to a vector of a fixed dimensionality, and then another deep LSTM to decode the target sequence from the vector.
++ So how to generate more efficient vector? You can use Attention mechanism.


# Dataset
 + an English to French translation task dataset WMT'14
 
 
# Algorithm
+ Model Structure
![Encoder-decoder structure](../Images/Encoder-decoder.png)
++ First, the input sequence (ABC) and the output sequence(WXYZ) have different length.
++ The decoder LSTM stops making prediction after outputing the end-of-sentence (EOS) token.
