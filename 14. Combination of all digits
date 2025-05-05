from itertools import permutations
digit1 = input("digit1 (0-9): ")
digit2 = input("digit2 (0-9): ")
digit3 = input("digit3 (0-9): ")
if all(d.isdigit() and 0<= int(d) <= 9 for d in [digit1,digit2,digit3]):
	digits = [digit1,digit2,digit3]
	combinations = set(permutations(digits, 3))
	for combo in sorted(combinations):
		print("".join(map(str, combo)))
else:
	print("Invalid")
