# Bigram seeral Pixel Language Model for MNIST

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![Dataset: MNIST](https://img.shields.io/badge/Dataset-MNIST-blue.svg)](http://yann.lecun.com/exdb/mnist/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A minimal PyTorch implementation of a nGram language model operating at the pixel level, adapted for MNIST handwritten digit generation. Part of foundational AI/ML studies aligned with long-term deep learning mastery goals.

## Output/Input (IO)

<table>
  <tr>
    <td>
      <div align="center">
        <img src="./img/input.png" alt="OUTPUT" width="300"/>
        <p>INPUTs</p>
      </div>
    </td>
    <td>
      <div align="center">
        <img src="./img/bigramslp.png" alt="SLP" width="300"/>
        <p>biGram SLP</p>
      </div>
    </td>
    <td>
      <div align="center">
        <img src="./img/ngrammlp.png" alt="MLP" width="300"/>
        <p>nGram MLP</p>
      </div>
    </td>
        <td>
      <div align="center">
        <img src="./img/ngrammlp.png" alt="CNN" width="300"/>
        <p>nGram CNN</p>
      </div>
    </td>
  </tr>
</table>



## Key Features

🖼️ **Pixel-level Generation** - Predicts next pixel intensity using bigram statistics  
🔢 **21-Class Classification** - Discretizes pixel values into 0.05 increments (0.0-1.0 range)  
📈 **Transformer Fundamentals** - Implements core language modeling concepts on image data  
🧮 **MNIST Adaptation** - Applies text-style modeling to 28x28 grayscale images  



