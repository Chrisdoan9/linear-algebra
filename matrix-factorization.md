## The original matrix A
| User \ Movie | M1 | M2 | M3 | M4 | M5 |
|------|----|----|----|----|----|
| U1   |  5 |  0 |  3 |  0 |  1 |
| U2   |  4 |  2 |  0 |  1 |  0 |
| U3   |  0 |  4 |  1 |  5 |  2 |
| U4   |  1 |  0 |  2 |  4 |  0 |

## The user “mixing” matrix W (4×2)
| User | Action/Adventure (F1) | Drama/Romance (F2) |
|------|-----------------------|---------------------|
| U1   | 0.9                   | 0.2                 |
| U2   | 0.8                   | 0.4                 |
| U3   | 0.1                   | 0.9                 |
| U4   | 0.3                   | 0.8                 |

## The movie “basis” matrix H (2×5)
| Factor \ Movie | M1  | M2  | M3  | M4  | M5  |
|--------|-----|-----|-----|-----|-----|
| F1     | 1.0 | 0.8 | 0.9 | 0.2 | 0.1 |
| F2     | 0.1 | 0.2 | 0.3 | 0.9 | 0.8 |

Reconstructing a rating: $\hat{A} = W \times H$
