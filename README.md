# Seq2Seq LSTM Encoder-Decoder Text Summarizer

## High-Level Architecture Overview

```
Dialogue → Transformer Encoder → Multi-Head Attention → Transformer Decoder → Summary
```

### Main Components
- Tokenizer & Vocabulary
- Positional Encoding
- Multi-Head Self-Attention
- Transformer Encoder (6 layers)
- Transformer Decoder (6 layers)
- Feed-Forward Networks
- Layer Normalization
- Loss Function (Cross-Entropy)

### Model Characteristics
| Feature | Description |
|---------|-------------|
| Model Type | Generative |
| Architecture | Transformer (Encoder-Decoder) |
| Attention | Multi-Head Self-Attention |
| Sequence Handling | Parallel processing |
| Output | Novel summary text |
| Training | Supervised |
| Decoding | Autoregressive |


### Dataset
TBD
