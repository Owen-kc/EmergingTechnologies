# EmergingTechnologies

# Tasks & Project
This repository is for Emerging Technologies, where we study the use of Quantum Computing as an emerging technology. The tasks in this repository are mainly mathematical operations in Python, while the project is a study on Deutsch's algorithm, which is a fundamental concept in quantum computing.

By *Owen Casey*

# Prerequisites
The main contents of this repository are Jupyter notebooks. To run these notebooks, you will need the following:

**Python**: Downloading the most recent version of Python is recommended. You can download python from the official Python site [here](https://www.python.org/downloads/). However, I recommend installing Python through [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) or [Anaconda](https://www.anaconda.com/download), as it provides an all in one installation and management for Python. 
- Miniconda (Recommended): Minimal installer, low storage usage
- Anaconda: Full installer, high storage usage 

**Jupyter Notebook**: Jupyter Notebook support should come with Anaconda/Miniconda, but you can also install it through a VSCode extension.

**Required Libraries**: Any required libraries will be mentioned in the relevant section they are used in the notebooks. 

**VSCode**: If you intend to execute code in your own environment, VSCode is recommended, as it's the standard.

# Anaconda and Miniconda
The use of Anaconda or Miniconda is *heavily* encouraged for this repository. Anaconda is a **full** installer while Miniconda is a **minimal** installer. They both have an easy to follow installer, which you can use to set up your environment. However, there are some things I'd like to mention. 

- When you install Anaconda/Miniconda, ensure that you have the correct environment set up in the interpreter for VSCode. To do this, you can:
    - Open VSCode
    - Install Python extension (if not already installed)
    - Open the command palette (Ctrl+Shift+P on windows / Cmd+Shift+P on Mac)
    - Enter "Python:Select Interpreter" and select it
    - Choose the correct Anaconda/Miniconda environment

-  If you haven't be sure to activate your environment through the command line. To do this, open the Anaconda/Miniconda command line and enter the following command:

```
conda activate myenv
```

Ensure that you replace "myenv" with your environment name.

- If you wish to install packages, extensions, etc, directly to your environment, you can use the following command:

```
conda install *package name*
```

- If required, ensure that you read any relevant documentation needed for [Anaconda](https://docs.anaconda.com/index.html) or [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/).

# How to run

This section provides a step-by-step guide on how to set up and run the Jupyter notebooks

### Step 1: Install Python
Ensure you have Python installed on your system. You can install it through the methods I outlined above.

### Step 2: Clone the Repository
Clone this repository to your local machine using Git. You can do this by running the following command in your terminal:
```
git clone https://github.com/Owen-kc/EmergingTechnologies.git
```

### Step 3: Install required libraries
The relevant libraries will be defined in the notebooks, ensure these are installed for the notebooks to run properly. Depending on how you have your own environment set up, you may want to install these locally in your Anaconda/Miniconda/VSCode terminal. Here is a list of extensions and libraries that are used in the notebooks:
- Qiskit
- Qiskit Aer
- Matplotlib
- Pandas
- Pylatexenc
- Itertools
- Numpy

### Step 4: Run Jupyter Notebook
If you have installed Anaconda or Miniconda, Jupyter Notebook should already be installed. Otherwise, install it using the following command:

```
pip install notebook
```
or you can install it through the VSCode extension.

### Step 5: Start Jupyter notebook

You can start the jupyter notebook you can run the following command:
```
jupyter notebook
```
You can use this command to open a navigation tree where you can select a specific notebook. **Note**: Depending on your own install, you may need to run this from your Anaconda/Miniconda terminal. If you are encountering errors launching the notebook in something like VSCode, you should open the Anaconda/Miniconda terminal, navigate to the repository using the following code command:

```
cd *path to repo on your system*
```

By following these steps, you should be able to run the contents of the repository.

# Tasks

## Overview
**Task 1: Collatz Conjuncture**
This task covers the famous unsolved Collatz Conjuncutre problem through Python.

**Task 2: Square Roots**
This task covers square roots in Python through Newtons method. 

**Task 3: Four Bit Functions**
This task covers a function that takes four input bits.

**Task 4: Matrix Multiplication**
This task covers matrix multiplication in Python.

# Project

## Overview
The project covers Deutsch's Algorithm, which is a foundational algorithm in quantum computing. The algorithm is the first representation of quantum advantage, which is when a quantum computer has an advantage over a classical computer. The project introduces quantum computing and gives a detailed explanation on all of the essential components for understanding and implementing Deutsch's algorithm.

In the project notebook, we create the quantum circuit for Deutsch's algorithm using Qiskit. Qiskit is an open source piece of software, developed by IBM for the purpose of quantum computing. You can find in depth documentation regarding Qiskit [here](https://www.ibm.com/quantum/qiskit).

## Purpose
The purpose of this project is to analyze Deutsch's algorithm and what purpose it serves in quantum computing. We aim to demonstrate Deutsch's algorithm being implemented in Qiskit, and simulate the quantum circuit we implement.

## Section Breakdown
Here, I will go over the main points of the project, and explain the purpose each of these sections represent.

### Introduction to Quantum Computing
Introduction to Quantum Computing covers the historical context and fundamentals of quantum computing. These aspects are essential to understanding the context of quantum computing before implementing Deutsch's algorithm. This section goes over the main points that we are interested in, qubits, superposition, entaglement and gates/circuits.

### Deutsch's Algorithm
This section introdices the concept of Deutsch's algorithm and what problem it aims to achieve. It provides context on balanced and constant functions, and introduces the oracle and the quantum circuit to the project.

### Qiskit
The Qiskit section introduces Qiskit, how to install it, and how it works. It provides a detailed explanation on Qiskit, including the components of Qiskit that we use in the implementation of Deutsch's algorithm, and provides a brief example of a simple cirucit.

### Deutsch's Algorithm in Qiskit
This is considered the main section of the notebook. Here, we implement Deutsch's algorithm in qiskit, and simulate the quantum circuit. This is the section we have been building towards with the previous sections.

### Results
In the results section, we provide an analysis of the results, as well as some scientifc graph representations of our results.

### Conclusion
Finally, we conclude our results and thoughts on Deutsch's algorithm in the conclusion section.


