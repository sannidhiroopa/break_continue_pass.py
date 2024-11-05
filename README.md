#Break Statement

av=5
x = int(input('how many candies you want?'))

i=1
while i<=x:
    if i==4:
        print('out of stock')
        break
    print('candy')
    i+=1
print('bye')
print()

#Continue Statement

for i in range(1,20):
    if i%3==0 or i%5==0:
        continue
    print(i)
print('bye')
print()

#Pass Statement

for i in range(1,15):
    if(i%2==0):
        pass
    else:
        print(i)
