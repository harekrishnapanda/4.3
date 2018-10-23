'''
In a class on 100 students, 80 students passed in all subjects, 10 failed in one subject, 7
failed in two subjects and 3 failed in three subjects. Find the probability distribution of
the variable for number of subjects a student from the given class has failed in.
'''

# 4.3
n = 100
x = 20
p = 0.5
prob = (math.factorial(n)/(math.factorial(x)*math.factorial(n-x)))*(p**x) *((1-p)**(n-x))
print ("Binomial Random Variable probability distribution =", prob)
