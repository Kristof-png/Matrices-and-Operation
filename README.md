matrix1 = np.array([[7, 11, 4],[12, 19, 1]])
matrix2 = np.array([[2, 0, 2],[2, 8, 3]])

print("Matrix 1:")
print(matrix1)
print("\nMatrix 2:")
print(matrix2)

matrix3 = matrix1 + matrix2
print("\nMatrix 3 (Matrix1 + Matrix2):")
print(matrix3)

matrix4 = matrix1 * 2
print("\nMatrix 4 (Matrix1 * 2):")
print(matrix4)

matrix5 = matrix2.T
print("\nMatrix 5 (Transpose of Matrix2):")
print(matrix5)

matrix6 = np.dot(matrix3, matrix5)
print("\nMatrix 6 (Matrix3 * Matrix5):")
print(matrix6)

sum_matrix3 = np.sum(matrix3)
print("\nSum of all elements in Matrix 3:")
print(sum_matrix3)

matrix7 = np.zeros((2,3), dtype=int)
print("\nMatrix 7 (Zero Matrix 2x3):")
print(matrix7)
