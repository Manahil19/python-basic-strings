# python-basic-strings
#1
txt="hello and welcome to my world"
x= txt.capitalize()
print(x)

#2
txt="36 is my age"
x=txt.capitalize()
print(x)

#3
txt="Hello AND WELCOME TO MY WORLD"
x=txt.casefold()
print(x)

#4
txt='banana'
x=txt.center(20)
print(x)
y=txt.center(10,"O")
print(y)

#5
txt="apple is my fav food,i like apples,,apples are good for health"
x=txt.count('apple')
print(x)

#6
txt = "I love apples, apple are my favorite fruit"
x = txt.count("apple", 1, 24)
print(x)

#7
txt='welcome to my world.'
x=txt.endswith(".")
print(x)

#8
txt1 = "My name is {fname}, I'm {age}".format(fname = "John", age = 36)
txt2 = "My name is {0}, I'm {1}".format("John",36)
txt3 = "My name is {}, I'm {}".format("John",36)
print(txt1)
print(txt2)
print(txt3)

#9
txt='i like bananas'
x=txt.replace('bananas','apple')
print(x)

#10
txt='company12'
x=txt.isalnum()
print(x)

#11
txt='python learning is easy and interesting'
x=txt.split()[::-1]
print(x)

#12
txt='company]'
x=txt.isascii()
print(x)
