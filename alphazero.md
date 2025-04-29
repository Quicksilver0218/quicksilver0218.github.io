---
layout: page
title: AlphaZero
permalink: /alphazero
---

# AlphaZero
A simplified AlphaZero implementation written in Python with TensorFlow and Keras.

The implementation is based on the [article](https://www.nature.com/articles/nature24270.epdf?author_access_token=VJXbVjaSHxFoctQQ4p2k4tRgN0jAjWel9jnR3ZoTv0PVW4gB86EEpGqTRDtpIz-2rmo8-KG06gqVobU5NSCFeHILHcVFUeMsbvwS-lxjqQGg98faovwjxeTUgZAUMnRQ){:target="_blank" rel="noopener noreferrer"}
published to Nature by David Silver, Julian Schrittwieser, Karen Simonyan et al.

Here is a demonstration with Tic-Tac-Toe.
![AlphaZero with Tic-Tac-Toe](/assets/images/AlphaZero.jpg)

You can run the demonstration program on [Kaggle](https://www.kaggle.com/code/quicksilver0218/alphazero-tic-tac-toe-demo){:target="_blank" rel="noopener noreferrer"} (an account is required).

You can also download the file to run the program on your computer.

[AlphaZero Tic-Tac-Toe Demo.zip](https://github.com/user-attachments/files/19959299/AlphaZero.Tic-Tac-Toe.Demo.zip)

If you have docker, you can build and run the image by executing `docker build and run.sh`.

You may also run the program directly on your machine. To run the program, you should have the prerequisites listed below.

## Softwares
- NVIDIA CUDA 11.2 ([Download](https://developer.nvidia.com/cuda-toolkit-archive){:target="_blank" rel="noopener noreferrer"})
- Python 3.10

## Python Packages
- typing_extensions 4.12
- NumPy 1.26
- TensorFlow 2.10
- Keras 2.10

Then, you can start with this command.
```
python -m games.mnk_game.executable.play
```
