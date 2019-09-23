# -Hardik-CS-CLASS-23-09-19-
python programs given on 23-09-19

#1).numbers divisible by 7 but not 5 between 2000 and 3200

print("numbers divisible by 7 but not 5 between 2000 and 3200 ")
a=2000
while(a<=3200):
    if(a%7==0 and a%5!=0):
        print(a)
    a+=1
    
    
#2). program to compute factorial

print("enter number to find factorial")
a=int(input())
k=a-1
while(k>0):
    a*=k
    k-=1
print(a)

#3). program to print i,i*i

num=int(input(" enter the number : "))
n=1
while(n<=num):
    print(n,':',n*n)
    n+=1


#4). program to print reverse

num=int(input("enter number : "))
num2=0
r=0
while(num>0):
    r=num%10
    num2=(num2*10)+r
    num=int(num/10)
print(num2)


#5). program to print sum of n numbers

num=int(input("enter the number n : "))
k=0
n=0
while(k<=num):
    n+=k
    k+=1
print(n)
