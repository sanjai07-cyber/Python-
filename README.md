# Python-
# LOOPs TASKS
'''
# task 1
for i in range(21):
    print(i)
'''
'''
#task2
num=int(input("Enter the to see its table:"))
for i in range(21):
    c=num*i
    print("the multiple of",num,"into",i,"is:",c)
'''
'''
#Task 3
for i in range(1,51):
    if i%2==0:
        print("the even number from 1 to 50",i,)
'''
'''
#task 4
a=int(input("Enter the number to see it's factorial:"))
fact=1
for i in range(1,a+1):
    fact=fact*i
print("the factoria; of the",a,"is:",fact)
'''
'''
#Task 6

for i in range(5):
    print("*"*i)
'''
'''
for i in range(5,0,-1):
    print("*"*i)
'''
'''
#Task 7
for i in  range (2,20+1):
    if i%2==0:
        print(i)
'''
'''
#Task8
a=0
while a<10:
    a+=1
    print(a)
'''
'''
#Task 9

a=0
while a<20:
    a+=1
    print(a)
'''
'''
#Task 10
a=11
while a>1:
    a-=1
    print(a)
'''

#LOOPS-2
'''
#task1
for i in range (1,100+1):
    print(i)
'''
'''
#Task2
for i in  range (1,30):
    if i%3==0:
        continue
    print(i)
'''
'''
#Task3
for i in range (1,20):
    if i%9==0:
        break
    print(i)
'''
'''
#Task4
for i in range (10):
    if i==5:
       pass
    print(i)
'''
'''
#task5
w="python"
for i in w:
    if i=='h':
        continue
    print(i)
'''
'''
#Task6
for i in range (10,-20,-1):
    if i<1:
        break
    print(i)
'''
'''
#Task7
count=20
while count>0:
    count-=1
    if count==17:
        continue
    
    if count==13:
        break
    print(count)
'''

#STRING
'''
#Task1
a=input("Enter your name:")
c=a.upper()
print(c)
'''
'''
#task2
a=input("enter the sentences:")
b=a.lower()
print(b)
'''
'''
#Task3
name=input("Enter your name :")
age=int(input("Enter your age :"))

print("my name is {} and age is {}".format(name,age))
'''
'''
#Task4
a=input("enter your name:")
c=a.capitalize()
print(c)
'''
'''
#Task 5
a="hello welcome"
b=a.index('e')
print(b)
''' 