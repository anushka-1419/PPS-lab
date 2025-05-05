# write your code here..
import math
a = float(input("a: "))
b = float(input("b: "))
c = float(input("c: "))
d = b**2 - 4*c*a
if d>0:
	root1 = (-b + math.sqrt(d)) / (2*a)
	root2 = (-b - math.sqrt(d)) / (2*a)
	print(f"The roots are: {root1:.2f} and {root2:.2f}")
elif d==0:
	root = -b / (2*a)
	print(f"The root is: {root:.2f}")
else:
	real_part = -b / (2*a)
	imag_part = math.sqrt(abs(d)) / (2*a)
	print(f"The roots are: {real_part:.2f}+{imag_part:.2f}j and {real_part:.2f}-{imag_part:.2f}j")
