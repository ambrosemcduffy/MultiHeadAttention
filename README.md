Multi‑Head Attention from Scratch (Educational PyTorch Implementation) 

This repository contains a  minimal, readable implementation of the core attention mechanisms used in the Transformer architecture: 

    Self‑Attention (used inside each encoder block)   
    Encoder‑Decoder Attention (used in the decoder to attend to encoder outputs)   
    Multi‑Head Attention (concatenating several independent attention “heads”) 

The code is deliberately kept simple—no fancy optimizations, no extra layers (like dropout or layer‑norm), and bias terms are omitted—to help you focus on the  math and tensor shapes that make attention work. 

    Why build it yourself?
    Implementing attention from scratch forces you to think through the linear projections, the scaled‑dot‑product, the masking trick, and the concatenation of heads. After you can follow the numbers, the high‑level Transformer diagrams become much clearer. 
