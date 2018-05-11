# 4.3
n = 100
x = 20
p = 0.5
prob = (math.factorial(n)/(math.factorial(x)*math.factorial(n-x)))*(p**x) *((1-p)**(n-x))
print ("Binomial Random Variable probability distribution =", prob)
