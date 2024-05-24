# Simulaix

An efficient synthetic data framework


---
Introduction to Simulaix:
- [About Simulaix](#about-simulaix)
    - [Why Simulaix?](#why-simulaix)
    - [Features](#features)
    - [Roadmap](#roadmap)
- [Installation](#installation)
    - [Usage](#usage)



## About Simulaix

Simulaix is a synthetic data generation framework that allows you to create synthetic data for machine learning and deep learning applications. It provides a simple and easy-to-use API to generate synthetic data for various applications. 


## Why Simulaix?

- **Simple**: Simulaix provides a simple and easy-to-use API to generate synthetic data. You can generate synthetic data with just a few lines of code.

- **Efficient**: Simulaix is designed to be efficient and fast. It uses modern libraries and techniques to generate synthetic data quickly.

- **Flexible**: Simulaix is flexible and allows you to customize the synthetic data generation process. You can specify the size, type, and other parameters of the synthetic data.

- **Scalable**: Simulaix is scalable and can generate synthetic data for large datasets. You can generate synthetic data for thousands or millions of samples with ease.




## Features
- [ ] simulaix api support
    - [ ] add face generation
    - [ ] add img generation

- [ ] add asynchronous support
- [ ] data augmentation support 
- [ ] data checking support
- [ ] data visualization and analysis support


## Installation

```sh 
# install from PyPI
pip install simulaix

```


## Usage

```python
import simulaix as sim

# create a synthetic data generator
generator = sim.Generator(type='face', size=(200, 200))
generator.generate(num_samples=1000, output_dir='data/face')

```



## Requirements
Python 3.7 or higher.