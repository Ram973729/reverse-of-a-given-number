# reverse-of-a-given-number
n=int(input('Enter any number:'))
s=0
while(n!=0):
    s=(s*10)+(n%10)
    n=n//10
print('Reverse number is',s) 
