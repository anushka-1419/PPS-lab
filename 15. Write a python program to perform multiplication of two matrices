def matmult(A, B):
	rowsA = len(A)
	colsA = len(A[0])
	rowsB = len(B)
	colsB = len(B[0])
	if colsA != rowsB:
		print("Cannot multiply the two matrices. Incorrect dimensions.")
		return None
	result = []
	for i in range (rowsA):
		row = []
		for j in range(colsB):
			row.append(0)
		result.append(row)
	for i in range(rowsA):
		for j in range(colsB):
			for k in range(colsA):
				result[i][j] += A[i][k] * B[k][j]
	return result


def readmatrix(name):
	# Write Code
	print(f"Enter values for matrix - {name}")
	m = int(input("Number of rows, m = "))
	n = int(input("Number of columns, n = "))
	matrix = []
	for i in range(m):
		row = []
		for j in range(n):
			value = int(input(f"Entry in row: {i+1} column: {j+1}\n"))
			row.append(value)
		matrix.append(row)
	return matrix


A = readmatrix("A")
B = readmatrix("B")
print("Matrix - A =", A)
print("Matrix - B =", B)
print("Matrix - A * Matrix- B =", matmult(A, B))
