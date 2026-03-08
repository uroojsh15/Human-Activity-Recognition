Assignment 5.4 – Recurrent Neural Network Based Classification

This project implements three recurrent neural network models for time-series classification: Simple RNN, LSTM, and GRU, using the WISDM accelerometer dataset.

Files included:
1. code.ipynb – Python notebook with full implementation:
   - Data loading and preprocessing
   - Sequence creation for RNN input
   - Model building (RNN, LSTM, GRU)
   - Training and evaluation
   - Plotting loss curves and confusion matrices

2. report.pdf – Analysis and discussion of results:
   - Performance comparison (accuracy, F1-score)
   - Training vs validation behavior
   - Confusion matrices
   - Comparison with fully connected neural network
   - Observed limitations

How to run:
- Install dependencies: numpy, pandas, scikit-learn, matplotlib, tensorflow
- Open `code.ipynb` in Jupyter Notebook
- Run all cells sequentially

Faster training settings (used for demonstration):
- Sequence length: 30
- Batch size: 64
- Epochs: 30
- Subset: 2000 training samples, 500 test samples

For full dataset training:
- Increase epochs (e.g., 10–30)
- Use full dataset for training/testing
- Recommended to use GPU for faster execution
