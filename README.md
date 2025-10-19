# day12
This prime number calculator will find if a number is prime or composite. Check for primality of any whole number up to 500 digits long.

What is a Prime Number?
A prime number is a whole number greater than 1 that is only divisible by 1 and itself. In other words, a prime number has only two factors, 1 and itself. A number that is not a prime is a composite number which means it has more than two factors.

How the Prime Checker Works
This prime number calculator checks whether a number is prime or composite using prime factorization. This means we divide your number by prime numbers until we find all its factors. If your number is not divisible by any prime number or composite number, your number is prime!

If your number is a composite number and less than 15 digits long, the calculator lists all factors of the composite number.


# the nmber has to div by that num and 1  is prime and take 2root of it and get the number and if you can devinthe main nmuber to the number of 2root is not prime number
# 75 root 2 is 8.6 divide 75 from 1 to 8 and 75 is posible to dvide by 3 so its is not prime number
import  math
def is_prime (num):
    def is_sqr (num):
        pri = 0
        sq_root = math.sqrt(num)
        # print(sq_root)
        sq_root =int(sq_root)
        for co in range(2,sq_root+1):
            val = num%co
            if val == 0:
                pri= 1
        return pri
    is_sqr(num)
    prime = is_sqr(num)
    # print(prime)
    def chnum_1 (num):
        if num%num == 0 and num%1 ==0:
            value = 0
        return value
    chnum_1(num)
    prime1 = chnum_1(num)
    # print(prime1)
    #
    if num == 1:
        print("nit")
    elif prime == 0 and prime1 == 0:
        print("prime number")
    else:
        print("not")
    



is_prime(100)

is_prime(100)
