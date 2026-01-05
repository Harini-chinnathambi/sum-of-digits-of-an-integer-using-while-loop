

sum=0
number=int(input("enter a integer:"))
while(number!=0):
    digit=number%10
    sum=sum+digit
    number=number//10
print("sum of digitd is:",sum)


Output:

enter a integer:46789
sum of digitd is: 34


