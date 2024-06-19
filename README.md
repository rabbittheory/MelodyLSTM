# MelodyLSTM

## Overview

This project began by exploring the use of LSTM (Long Short-Term Memory) neural networks to generate music MIDI sequences. However, the approach later shifted to using RNNs (Recurrent Neural Networks) as they produced better results. The model learns from a dataset of MIDI files and generates new music based on learned patterns, incorporating randomization to create notes with sequential similarity.
## Features

**Dataset**:  
The project uses a subset of MIDI files containing musical sequences from the MAESTRO Dataset. MAESTRO (MIDI and Audio Edited for Synchronous Tracks and Organization) is a dataset composed of approximately 200 hours of virtuosic piano performances, captured with fine alignment (~3 ms) between note labels and audio waveforms.

**Model**:  
An Recurrent Neural Network is trained to predict the next musical note based on previous notes.

**Normalization/Denormalization**:  
MinMaxScaler is used for normalization and denormalization of the data.

**Randomization/Variety**:  
Randomized note values from the seed sequence are included to prevent overly repetitive patterns.

**Generation**:  
The model generates music sequences and saves them as MIDI files.

---

### Prerequisites

- Python
- PyTorch
- NumPy
- pretty_midi
- sklearn
