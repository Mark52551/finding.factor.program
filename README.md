# finding.factor.program
This program I created for finding the factors of a number. 


def max_number():
    max_num= int(input("Enter an upper limit number : "))
    return mix_num

def number():
    number= int(input("Enter a factorial number : "))
    return number

def find_all_factors(max_num, number):
    while number <= max_num:
        if max_num % number == 0:
            print (number)
        number= number +1
def find_perfect_numbers(max_num):
    return [i for i in range(number, max_num+1) if sum(ifactors(i)) + 1 == i]


#****------------------------MAIN------------------****


#welcome
print ("Welcome to Perfect Number Program!")
print ("")
#get the max number
#get the upper limit
max_num= int(input("Enter an upper limit number : "))
#get the factors
number= int(input("Enter the factorial number : "))

find_all_factors(max_num, number)
