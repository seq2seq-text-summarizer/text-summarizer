# Seq2Seq LSTM Encoder-Decoder Text Summarizer

## High-Level Architecture Overview

```
Long Text → Encoder LSTM → Context Vector → Decoder LSTM → Summary
```

### Main Components
- Tokenizer & Vocabulary
- Encoder (LSTM)
- Context Vector (Hidden & Cell States)
- Decoder (LSTM)
- Softmax Output Layer
- Loss Function (Cross-Entropy)

### Dataset
[kaggle/newspaper-text-summarization-cnn-dailymail](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail/)
