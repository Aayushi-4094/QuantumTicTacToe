
# Quantum Tic-Tac-Toe with Quantum Superposition

This repository contains a Python script for a Quantum Tic-Tac-Toe game that leverages Quantum Superposition using Qiskit and Streamlit. Players can enjoy a unique twist on the classic game by experiencing the quantum effects of superposition. The game is built to help beginners understand Quantum Superposition in a fun and interactive way.

## Dependencies

Before running the game, make sure you have the following dependencies installed:

- Qiskit 0.37
- Qiskit Aer 0.11
- Streamlit
- LocalTunnel (for deployment)

You can install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## Running the Game

To run the game, follow these steps:

1. Install the dependencies using the provided `requirements.txt` file.

2. Run the Streamlit app with the following command:

```bash
streamlit run app.py &>/content/logs.txt & curl ipv4.icanhazip.com
```

3. Access the game using the provided IP address in your web browser.

## Code

```python
!pip install qiskit==0.37
!pip install qiskit-aer==0.11
import qiskit
from qiskit import QuantumCircuit, Aer
from qiskit_aer import AerSimulator
import numpy as np
import streamlit as st
import math

# Quantum Superposition Function and Tic-Tac-Toe Game Logic code goes here...
```

## Game Features

- **Quantum Superposition:** Quantum superposition is used to determine the state of each square in the Tic-Tac-Toe grid, adding an element of randomness to the game.

- **Interactive Gameplay:** Players can take turns making moves on the 3x3 grid using a web-based interface created with Streamlit.

- **Instructions:** The game provides instructions for playing Quantum Tic-Tac-Toe and learning about Quantum Superposition.

## About

The Quantum Tic-Tac-Toe game is created by Aayushi Agarwal as a fun and educational way to understand Quantum Superposition. Players can explore the quantum effects of superposition while enjoying a classic game.

## Google Colab Link

[Google Colab Link](https://colab.research.google.com/drive/11NxG_BhD2aRdxb0SrdzDvSCyvATc7Egg?usp=sharing)

## References

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [Streamlit Documentation](https://streamlit.io/docs/)
- [LocalTunnel Documentation](https://github.com/localtunnel/localtunnel)

Feel free to explore and contribute to the game. Enjoy playing Quantum Tic-Tac-Toe with Quantum Superposition!

This README includes the Google Colab link and provides comprehensive instructions for running the game, along with an overview of its features and background information. Feel free to customize it further as needed!

## Images

<img width="1440" alt="Screenshot 2024-05-03 at 9 50 07 AM" src="https://github.com/Aayushi-4094/QuantumTicTacToe/assets/97082852/cecfb977-97ef-479c-a31f-f7a1910bdcd5">
<img width="1440" alt="Screenshot 2024-05-03 at 9 49 58 AM" src="https://github.com/Aayushi-4094/QuantumTicTacToe/assets/97082852/5393f14f-b9e7-4666-9b97-68607d271825">
<img width="1440" alt="Screenshot 2024-05-03 at 9 49 31 AM" src="https://github.com/Aayushi-4094/QuantumTicTacToe/assets/97082852/99c420fe-8c06-4eaf-875f-bed3e54a508a">
<img width="1440" alt="Screenshot 2024-05-03 at 9 49 21 AM" src="https://github.com/Aayushi-4094/QuantumTicTacToe/assets/97082852/aa5c6914-9fb9-4793-9de4-5a2a6b8d481d">
