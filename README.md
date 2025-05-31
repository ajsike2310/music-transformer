# Music Transformer

A PyTorch-based implementation for symbolic music generation using the Music Transformer architecture. This project leverages the MAESTRO dataset and provides tools for training, generating, and experimenting with music sequences in MIDI format.

## Features
- Train a Music Transformer model on the MAESTRO dataset
- Generate new music pieces in MIDI format
- Jupyter notebook for experimentation and visualization
- Support for custom datasets

## Project Structure
```
├── maestro-v2.0.0-midi/         # MAESTRO dataset (MIDI files)
├── maestro-v2.0.0-midi.zip      # Zipped dataset (not tracked by git)
├── maestro-v3.0.0.json          # Dataset metadata
├── music_transformer.pth        # Pretrained model weights (not tracked by git)
├── my_generated_piece.mid       # Example generated MIDI file
├── requirements.txt             # Python dependencies
├── transform.ipynb              # Jupyter notebook for training/generation
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/ajsike2310/music-transformer.git
   cd music-transformer
   ```
2. (Recommended) Create and activate a virtual environment:
   ```sh
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # source venv/bin/activate  # On Linux/Mac
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
- Open `transform.ipynb` in Jupyter Notebook or VS Code.
- Follow the notebook cells to train the model or generate new music.
- Place your MIDI files in the `maestro-v2.0.0-midi/` directory if using a custom dataset.

## Dataset
- The project uses the [MAESTRO dataset](https://magenta.tensorflow.org/datasets/maestro) for training and evaluation.
- Download and extract the dataset into the `maestro-v2.0.0-midi/` folder.

## Model
- The Music Transformer model is saved as `music_transformer.pth` after training.
- Pretrained weights are not included in the repository due to size.

## Requirements
- Python 3.8+
- See `requirements.txt` for all dependencies

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgements
- [Magenta](https://magenta.tensorflow.org/)
- [MAESTRO Dataset](https://magenta.tensorflow.org/datasets/maestro)
- [Music Transformer Paper](https://arxiv.org/abs/1809.04281)
