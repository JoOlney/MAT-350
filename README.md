# MAT-350
Applied Linear Algebra: SNHU 2024

Lab scripts written and executed in MATLAB via the zyLab environment.

Topics Covered:

Matrices & Systems:
Matrix arithmetic: addition, subtraction, scalar multiplication, matrix products,
Determinants (det()), Cramer's Rule for solving linear systems,
Row reduction (rref()), rank (rank()), null space (null())

Vectors:
Dot products (dot()) using both the dot() command and matrix multiplication,
Cross products (cross()) and volume of a parallelepiped (scalar triple product),
Vector and matrix norms: 2-norm, p-norm, infinity-norm, Frobenius norm (norm()),
Euclidean distance between vectors and matrices

Vector Spaces:
Determining if a set of vectors spans a space,
Finding a basis for the null space and extending a set to a basis,
Change of coordinates matrix between two bases (rref() on augmented matrix [C | B])

Linear Transformations:
Rotation matrices: transforming points counterclockwise by angle θ,
Matrix representation of a transformation with respect to ordered bases B and C

Eigenvalues & Decompositions:
Characteristic polynomial (poly()) and eigenvalues (roots(), eig()),
Diagonalization: finding P and D such that A = PDP⁻¹, used to compute Aⁿ efficiently,
QR factorization (qr()): Q orthogonal, R upper triangular,
Singular value decomposition (svd()): A = USVᵀ,
Pseudoinverse (pinv()) for non-square matrices

Applications:
Least squares best-fit line and best-fit parabola using overdetermined systems

Reflection:

Linear algebra's real power became clear when the MATLAB labs connected the theory to computation. Row reduction is the same operation whether you are solving a system of equations, finding a null space, or computing a change-of-basis matrix — the rref() command made that structural unity visible in a way that hand calculations can obscure. The decomposition labs (eigenvalues, QR, SVD) were the most illuminating. Diagonalization turns a repeated matrix power — computationally expensive — into a simple scalar operation on the diagonal entries of D. SVD showed how any matrix can be broken into three interpretable pieces: rotation, scaling, and rotation again. These are not just theoretical results; they are the foundation of image compression, data science, and machine learning, which gave every proof and computation a concrete purpose.
