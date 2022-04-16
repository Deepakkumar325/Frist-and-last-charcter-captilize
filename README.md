# Frist-and-last-charcter-captilize
#frist and last charcter in python

s=input("string")

s=s.title()

w=s.split()

r=''

for i in w:
    
    r=r+i[:-1]+i[-1].upper()+''

print("new string\n",r)
