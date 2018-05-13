# python-practice
#homework for python:log in with password and name

count=0   #count how many times you try
while count<3:
    name =input("name:")
    password = input("password:")
    if name=="Jack" and password=="123":
        print("Welcome!")
        break
    else:
        print("Wrong!")
    count+=1
else:
    print("You try too many times!")
