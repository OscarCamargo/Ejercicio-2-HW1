# Ejercicio-2-HW1
def factorial(n):
    for i in xrange(n-1,1,-1):
        n *= i
    return n
lim = 25
a, b = 1,1
for i in xrange(lim):
    if (factorial(a-1)+1)%a==0 and a != 1:
        print(a)
    a, b = b, a + b

# La mayor cantidad de primos en la sucesión de Fibonacci que logré calcular con este programa fue 8 números primos.
