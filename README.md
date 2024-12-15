# Lion Gold Price Predictor

Transformer-based model for short-term gold price prediction.

## Features
- 0-60 minute predictions with 10-minute resolution
- Confidence intervals
- Cross-asset input (Gold, USDX, US Bonds)
- GPU-optimized

## Setup
1. Install requirements
2. Place CSV files in root directory
3. Run `main.py`

## Model Architecture
- Transformer encoder
- Probabilistic output
- Multi-asset feature engineering

## Usage
```python
python main.py
```