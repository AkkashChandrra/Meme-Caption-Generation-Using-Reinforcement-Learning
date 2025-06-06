Meme Caption Generator with A2C Reinforcement Learning
Overview
This project generates viral meme captions using a 6992-image dataset, leveraging an A2C-reinforced LSTM with attention and ViT CLIP for context-aware captions. Built with Python, PyTorch, and NLTK, it achieves 42% humor, 66.3% reward, 96% coherence, and 11.84% BLEU, outperforming T5 (40% reward). Example: “EMOTIONAL DAMAGE #POLITICIAN” for politician memes.
Features

A2C RL: Fine-tunes captions with human-centered rewards.
LSTM with Attention: Models sequences for coherent captions.
ViT CLIP: Extracts image keywords (e.g., “ZOMBIE”) for context.
Slang Integration: Uses “RIZZ”, “SHEESH” for viral appeal.
Metrics Visualization: Matplotlib plots for humor, coherence.

Requirements

Python 3.8+
PyTorch, NLTK, Matplotlib, CLIP, Pandas, NumPy
Dataset: 6992 Labeled Meme Images
Results

Humor: 42% (1.26/3.0)
Reward: 66.3% (6.63/10)
Coherence: 96% (0.96/1.0)
BLEU: 11.84%
Surpasses T5 baseline (40% reward) with context-aware, slang-rich captions.

Contributing
Pull requests welcome! Open issues for bugs or feature requests.
License
MIT License
