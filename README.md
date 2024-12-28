# PageRank Implementation in Python

This repository contains a Python-based implementation of the PageRank algorithm, a foundational algorithm for ranking nodes in a graph, widely known for its application in search engines like Google. The notebook demonstrates the computation of PageRank values for graph nodes and includes examples and explanations for better understanding.

## Features
- Implement PageRank and Personalized PageRank step-by-step from scratch with explain and visualization
- Use as a recommendation system with several other methods on some graph data
## Getting Started

### Prerequisites
To run the notebook, you'll need:
- Python 3.7 or later
- Jupyter Notebook
- Libraries: `numpy`, `matplotlib`, `networkx`

Install the required libraries using:
```bash
pip install numpy matplotlib networkx
```

### Running the Notebook
1. Clone this repository:
2. Follow the instructions in the notebook to compute PageRank values for a sample graph or your own custom graph.

## How It Works
The PageRank algorithm assigns a ranking to each node in a graph based on the structure of incoming and outgoing edges. It is defined as:
```
\[ PR(v) = (1 - d) + d \sum_{u \in B(v)} \frac{PR(u)}{L(u)} \]
```
Where:
- **PR(v):** PageRank value for node \(v\)
- **d:** Damping factor (typically set to 0.85)
- **B(v):** Set of nodes linking to \(v\)
- **L(u):** Number of outbound links from node \(u\)

The algorithm iteratively updates the PageRank values until convergence.

## Example Output
Example graph visualizations and PageRank results are provided within the notebook to illustrate the algorithm's effectiveness.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments  
This notebook was adapted from [network-science course](https://github.com/netspractice/network-science/tree/main). 


---

Enjoy exploring PageRank with this implementation!


