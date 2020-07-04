# lockdownrepository
a = []
for i in range (0,5):
  a.append(i**2)
  print("inside of for loop",a)
print("outside of for loop:",a)

#oddeven
all = [1,2,3,4,5]
even = []
odd = []
for i in all:
  if(i%2 == 0):
    even.append(i)
  else:
		odd.append(i)
print(even)
print(odd)
