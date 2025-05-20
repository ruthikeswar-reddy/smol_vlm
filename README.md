# SmolVLM

SmolVLM is a lightweight Vision Language Model implementation that leverages Hugging Face's transformers library for efficient image-text understanding tasks. The project includes implementations for Visual Instruction Navigation (VIN) and License Plate Detection (LPD) tasks.

## Project Structure

```
smolVLM/
├── data/           # Directory for storing datasets and model weights
├── notebooks/      # Jupyter notebooks for experiments and examples
│   ├── smolvlm_lpd.ipynb  # License Plate Detection implementation
│   └── smolvlm_vin.ipynb  # VIN Detection
├── smolVLM/        # Main package directory
└── requirements.txt # Project dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/smolVLM.git
cd smolVLM
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Dependencies

The project requires the following main dependencies:
- torch
- torchvision
- torchaudio
- einops
- timm
- pillow
- transformers
- huggingface-hub

## Features

- Lightweight Vision Language Model implementation
- Integration with Hugging Face's transformers library
- Support for various image-text understanding tasks including:
  - Visual Instruction Navigation (VIN)
  - License Plate Detection (LPD)
- Jupyter notebook examples for each implemented task

## Usage

The project includes two main implementations:

1. ** (VIN)**
   - Located in `notebooks/smolvlm_vin.ipynb`
   - Implements navigation tasks based on visual and textual instructions

2. **License Plate Detection (LPD)**
   - Located in `notebooks/smolvlm_lpd.ipynb`
   - Implements license plate detection and recognition

To get started, open the respective Jupyter notebooks in the `notebooks` directory and follow the examples.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Ruthikeswar]

## Acknowledgments

- Hugging Face for their excellent transformers library
- The open-source community for various tools and libraries used in this project 
