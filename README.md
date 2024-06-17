# Music Generation with LSTM

## Overview

This project explores using LSTM (Long Short-Term Memory) neural networks to generate music MIDI sequences. The model learns from a dataset of MIDI files and generates new music based on learned patterns.

## Features

- **Dataset**: Uses MIDI files containing musical sequences from MAESTRO Dataset.
MAESTRO (MIDI and Audio Edited for Synchronous Tracks and Organization) is a dataset composed of about 200 hours of virtuosic piano performances captured with fine alignment (~3 ms) between note labels and audio waveforms.
- **Model**: LSTM neural network trained to predict the next musical note based on previous notes.
- **Normalization/Denormalization**: Converts normalized features back to MIDI-compatible format.
- **Generation**: Generates music sequences and saves as MIDI files

## Setup

### Prerequisites

- Python 3.x
- PyTorch
- NumPy
- pretty_midi

