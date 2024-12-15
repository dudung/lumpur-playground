# lumpur-playground

This repository contains example Jupyter notebooks demonstrating how to use the [`lumpur`](https://pypi.org/project/lumpur/) Python package. These examples are designed for students and anyone interested in learning how to use the package effectively for simulations, data modeling, and visualization.

---

## Getting Started

### Installation
To use the examples in this repository, you need to have the `lumpur` package installed. You can install it via pip:

```bash
pip install lumpur
```

Additionally, fork this repository and then clone it to access the notebooks:

```bash
git clone https://github.com/your-username/lumpur-playground.git
cd lumpur-playground
```

Replace `your-username` with your GitHub username when cloning the forked repository.

### Environment Setup
To ensure compatibility with the notebooks, install the required dependencies:

- If using `requirements.txt`:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  pip install -r requirements.txt
  ```

- If using `environment.yml` (for Conda users):
  ```bash
  conda env create -f environment.yml
  conda activate lumpur-playground
  ```

### Running the Notebooks
To explore the examples, launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the desired notebook from the `notebooks/` folder and run the cells.

---

## Examples

### Available Notebooks

1. **Introduction**
   - Notebook: `notebooks/introduction.ipynb`
   - Overview of the `lumpur` package and its main features.

2. **Polynomial Examples**
   - Notebook: `notebooks/polynomial_examples.ipynb`
   - Demonstrates how to create and manipulate polynomials using the `num.Polynomial` class.

3. **Linear Regression Examples**
   - Notebook: `notebooks/regression_examples.ipynb`
   - Shows how to perform simple linear regression using the `fit.LinearRegression` module.

4. **Simulation Examples**
   - Notebook: `notebooks/simulation_examples.ipynb`
   - Explains grid-based and random walk-like simulations with examples from the `sim` module.

### Additional Resources
Each notebook includes:
- Step-by-step instructions.
- Code snippets.
- Visualizations (if applicable).

---

## Contributing
Contributions are welcome! If you have suggestions for new examples or improvements, please open an issue or submit a pull request.

### How to Contribute
1. Fork this repository.
2. Create a new branch for your contributions:
   ```bash
   git checkout -b feature/new-example
   ```
3. Add your notebook or modify an existing one.
4. Commit your changes and push them to your fork.
5. Submit a pull request.

---

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
This repository is maintained by Sparisoma Viridi. It is an educational resource for learning and teaching with the `lumpur` package.
