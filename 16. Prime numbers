def is_prime(num):
	if num <= 1:
		return False
	for i in range (2,int(num**0.5) + 1):
		if num%i == 0:
			return False
	return True
def print_primes(n):
	for num in range(2,n):
		if is_prime(num):
			print(num, end="\n")
n = int(input("Enter upper limit: "))
print_primes(n)
