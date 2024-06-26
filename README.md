# Data Structures and Algorithms

Welcome to the "Data Structures and Algorithms" repository! This project is a collection of Python implementations 
and tests for fundamental data structures and algorithms, aimed at helping me enhance my problem-solving skills and understanding of key concepts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Automated Testing with GitHub Actions](#automated-testing-with-github-actions)
- [License](#license)

## Introduction

This repository serves as a comprehensive learning resource and practical reference for various data structures and algorithms commonly used in computer science and software development. Each implementation is designed to be efficient, reliable, and well-documented to aid understanding and foster best coding practices.

## Features

- Python implementations of essential data structures: linked lists, stacks, queues, hash tables, binary search trees, graphs, tries, and heaps.
- Python implementations of fundamental algorithms: linear search, binary search, bubble sort, merge sort, depth-first search, Dijkstra's shortest path, dynamic programming, and more.
- Comprehensive unit tests for each data structure and algorithm to ensure correctness and reliability.
- Detailed documentation and explanations for each implementation, including time and space complexity analysis.
- Real-world use cases demonstrating the practical application of data structures and algorithms.

## Getting Started

To get started with this project, you need to have Python installed on your system. If you want to use Docker, ensure you have Docker and docker-compose installed.

1. Clone the repository:

```bash
git clone https://github.com/Ebi27/DataStructuresAndAlgorithms.git
cd DataStructuresAndAlgorithms
```

2. (Optional) Set up a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## File Structure
The repository's file structure is organized as follows:

- `Netflix/`: Contains Python implementations of various features improving the user experience in finding content to watch. This involves the improvement of the search as well as recommendation functionality.
- `tests/`: Contains unit test files for each data structure and algorithm.
- `Dockerfile`: Used for Docker containerization.
- `docker-compose.yml`: Configuration for running the project in Docker.
- `requirements.txt`: List of required Python dependencies.
- `README.md`: The document you are currently reading.


## Automated Testing with GitHub Actions

This project includes automated testing using GitHub Actions. 
On every push to the main branch, the tests will be automatically executed using the pytest framework to ensure the correctness of the implementations. 


## Usage

After setting up the project, you can run the unit tests to ensure all implementations are correct:

```bash
python -m unittest discover -s tests
```

Feel free to explore the code, use the implementations in your own projects, and contribute to this repository.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.