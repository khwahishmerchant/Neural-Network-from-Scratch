# Simple Neural Network from Scratch

This project demonstrates a simple neural network implemented from scratch in Python, using only NumPy. It is a great starting point for understanding the basics of neural networks, forward propagation, and backpropagation.

## Features

- No external machine learning libraries (only NumPy)
- Illustrates the core principles of neural networks and training
- Solves the classic XOR problem

## How it works

- The network consists of an input layer, one hidden layer with 4 neurons, and an output layer.
- Uses the sigmoid activation function.
- Trains on the XOR dataset using manual backpropagation.

## Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```

2. **Install dependencies**  
   (If you don’t have NumPy)
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the code**  
   ```bash
   python neural_network.py
   ```

## Output

After training, the script prints the learned weights and the final output prediction of the network.

## Example Output

```
[[...weights1 values...]]
[[...weights2 values...]]
[[0.01...]
 [0.98...]
 [0.98...]
 [0.01...]]
```

## Files

- `neural_network.py` – Main code file
- `requirements.txt` – List of dependencies
- `.gitignore` – Standard Python ignores

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Created by [Your Name](https://github.com/YOUR-USERNAME)*