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
   git clone https://github.com/khwahishmerchant/Neural-Network-from-Scratch.git
   cd Neural-Network-from-Scratch
   ```

2. **Install dependencies**  
   (If you don’t have NumPy installed, run:)
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the code**  
   ```bash
   python neural_network.py
   ```

> **Note:** This code is compatible with Python 3.x.

## Output

After training, the script prints the learned weights and the final output prediction of the network.

## Example Output

```
[[ 7.83466268  5.12410097 -4.15922602  3.09272652]
 [-4.83734023  5.00927678  7.71354398  2.98261113]
 [ 1.37657582 -0.35817953  0.78073725  1.5943769 ]]
[[-10.50703467]
 [  9.54010585]
 [-10.51223769]
 [  6.44099356]]
[[0.00179643]
 [0.9932753 ]
 [0.99323431]
 [0.00836755]]
```

## Files

- `neural_network.py` – Main code file
- `requirements.txt` – List of dependencies
- `.gitignore` – Standard Python ignores

---

*Created by [Khwahish Merchant](https://github.com/khwahishmerchant)*
