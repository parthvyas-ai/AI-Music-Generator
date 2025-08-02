# AI-Music-Generator

## Project Overview:
With the use of  LSTM-based neural network to learn musical patterns from a collection of MIDI files and generate new sequences in the style of classical piano music.
Key Concepts:
- MIDI Parsing with music21
- Sequence generation for time series (notes/chords)
- Multi-layer LSTM model with dropout regularization
- Generation of new music and conversion to playable .mid files

## Quick Access
Open in Google Colab - https://colab.research.google.com/drive/1sKswbTLMzu0SymAylr0AfRQZFBChnN_m?usp=sharing

## Model Architecture
- 3 stacked LSTM layers (512 units each)
- Dropout (0.3) for regularization]
- Dense layer to map to output vocabulary
- Softmax activation to predict next note/chord


