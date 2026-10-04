# gram-schmidt-orthogonalization

Python implementation of Gram-Schmidt orthogonalization, part of a Linear Algebra mini project on orthogonal matrices and 3D graphics (team of four).

## What it does

Takes linearly independent vectors v₁, ..., vₙ and builds an orthonormal set:

- u₁ = v₁
- u_k = v_k − Σ proj(v_k onto u_j), for j < k
- e_k = u_k / ‖u_k‖

Putting e₁, ..., eₙ as columns gives Q, an orthogonal matrix (QᵀQ = I).

## How to run

    pip install numpy matplotlib
    python gram_schmidt.py

## Full project

Part of our team project:  https://github.com/nam-sketch-sys/orthogonality-matrix-mini-project
