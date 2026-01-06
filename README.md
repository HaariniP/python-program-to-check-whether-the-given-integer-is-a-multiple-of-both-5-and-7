# python-program-to-check-whether-the-given-integer-is-a-multiple-of-both-5-and-7
number=int(input("Enter an integer:"))
if((number%5==0)and(number%7==0)):
    print(number,"is a multiple of both 5 and 7")
else:
    print(number,"is not a multiple of both 5 and 7")

output
Enter an integer:50
50 is not a multiple of both 5 and 7
Enter an integer:35
35 is a multiple of both 5 and 7

