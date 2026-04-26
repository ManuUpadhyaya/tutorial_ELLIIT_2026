# ELLIIT 2026 Tutorial: Computer-Aided Lyapunov Analyses

This repository contains the material for the ELLIIT 2026 Lund tutorial on computer-aided Lyapunov analyses with AutoLyap.

## Suggested path

1. Read the [slides](slides.pdf)
2. Complete the [proximal gradient method exercise](notebooks/proximal_gradient_method.ipynb)
3. Run the two iteration-independent examples
4. Run the iteration-dependent example

The exercise asks you to fill in the state-space matrices before running the
Lyapunov search. The three example notebooks are fully filled in and can be run
from top to bottom.

## Run in Google Colab

No local installation is needed. Open a notebook below in Colab.

| Material | Use this for | Open |
| --- | --- | --- |
| Proximal gradient method exercise | Fill in \(A,B,C,D\), validate them, then run the Lyapunov search | [Colab](https://colab.research.google.com/github/ManuUpadhyaya/tutorial_ELLIIT_2026/blob/main/notebooks/proximal_gradient_method.ipynb) |
| Iteration-independent example 1 | Davis--Yin three-operator splitting | [Colab](https://colab.research.google.com/github/ManuUpadhyaya/tutorial_ELLIIT_2026/blob/main/notebooks/iteration_independent_lyapunov_example_1.ipynb) |
| Iteration-independent example 2 | Gradient method with constant Nesterov momentum | [Colab](https://colab.research.google.com/github/ManuUpadhyaya/tutorial_ELLIIT_2026/blob/main/notebooks/iteration_independent_lyapunov_example_2.ipynb) |
| Iteration-dependent example | Nesterov fast gradient method | [Colab](https://colab.research.google.com/github/ManuUpadhyaya/tutorial_ELLIIT_2026/blob/main/notebooks/iteration_dependent_lyapunov_example.ipynb) |

For the three example notebooks, choose `Runtime > Run all`. For the exercise
notebook, fill in the missing matrices first; the notebook includes a quick
validation cell before the SDP search.

The notebooks install AutoLyap automatically in Colab. Some cells solve
semidefinite programs and may take a few minutes; progress is printed during
the longer sweeps.
