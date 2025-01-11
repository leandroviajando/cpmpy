# CPMpy

## Setup

```bash
pyenv local 3.11.9
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements-dev.txt
pip install -r requirements.txt
```

### Generate PDFs

```bash
mkdir -p pdfs && \
  echo "*" > pdfs/.gitignore && \
  jupyter nbconvert --to pdf --output-dir=pdfs session[1-6]*.ipynb
```

## [1. Declarative Modelling](./session1-modelling.ipynb)

## 2. Solving Techniques

### [2.1. Debugging](./session2_a-debugging.ipynb)

### [2.2. Solving](./session2_b-solving.ipynb)

### [2.3. Explaining](./session2_c-explaining.ipynb)

### [2.4. Reification](./session2_d-reification.ipynb)

## [3. Global Constraints](./session3-global_constraints.ipynb)

## [4. Modelling Techniques](./session4-viewpoints-channelling-auxiliary_variables-implied_constraints.ipynb)

### 4.1. Viewpoints

### 4.2. Channelling

### 4.3. Auxiliary Variables

### 4.4. Implied Constraints

## [5.1. Decompositions](./session5_a-decompositions-problem_aware-solver_aware.ipynb)

### 5.1.1. Problem-Aware Decompositions

### 5.1.2. Solver-Aware Decompositions

### 5.1.3. Low-Level Modelling

## [5.2. Algorithm and Hyperparameter Selection and Configuration](./session5_b-algorithm_selection-algorithm_configuration-hyperparameter_configuration.ipynb)

### 5.2.1. Algorithm Selection

### 5.2.2. Algorithm Configuration

### 5.2.3. Hyperparameter Configuration

## [6. Symmetry and Dominance Breaking](./session6-symmetry-dominance_breaking.ipynb)
