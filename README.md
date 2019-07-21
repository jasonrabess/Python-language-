# Python-language-
Python language skill level
print("Hello World")
Hello World
 
# comment line for reminders
print("hello program !")
hello program !
# intergers are any whole numbers
print (1,2,3,4)
1 2 3 4
# A interger string text
print("1,2,3,4")
1,2,3,4
# variables are name containers
print ("stock_price")
stock_price
# Variable can hold strings 
current_message="I am a cipher"
print (current_message)
I am a cipher
# Variable as data type
stock_price=45.00
print("how much is worth this stock",stock_price)
how much is worth this stock 45.0
# type returns the data type of the function
type("hello world")
str
type (0.1)
float
type (1)
int
# numeric equation single line math addition
3+6
9
# single line concatenated string
print("i don't wear","any hats")
i don't wear any hats
# users prompt using input
cipher_name=input("enter ciphers name:")
print ("hi", cipher_name)
enter ciphers name:jason
hi jason
print('i said "i can not stop the change "')
i said "i can not stop the change "
# single quotes in double quotes , double quotes in single quotes
print("It's time to save your code")
It's time to save your code
# string format methods
print("cipher is workin in his office".capitalize())
Cipher is workin in his office
fav_color=input('what is your favorite color?: '.lower())
print("so your favorite color is" , fav_color)
what is your favorite color?: white
so your favorite color is white
fav_color=input('what is your favorite color?: ').upper()
print("so your favorite color is " , fav_color)
what is your favorite color?: white
so your favorite color is  WHITE
print("fav_color".swapcase())
FAV_COLOR
print("fav_color".title())
Fav_Color
# searching string sequence
menu=("salad,drink,pizza,bread")
print('bread' in menu)
True
menu=("salad,drink,pizza,bread")
print('chips'in menu)
False
# defining a function 

def say_hi():
    print('hello there')
    print('goodbye')
 
say_hi()
hello there
goodbye
def yell_this (phrase):
    print(phrase.title()+ "!")
yell_this("now time to sleep")
    
Now Time To Sleep!
# create a function with a return

def msg_double (phrase):
    double=( "please let us go please").upper()
    return double
msg_2x =msg_double('let us go')
print(msg_2x)
PLEASE LET US GO PLEASE
# sequence 


def hat_available(color):
    hat_colors =('black, red, blue, green, white, grey, brown, pink' ) 
    return(color.lower() in hat_colors)
have_hat=hat_available('blue')
print('hat available is', have_hat)
hat available is True
def how_many():
    requested=input("please enter how many u want:")
    return requested
    
number_needed=how_many()
print(number_needed,"will be order")
please enter how many u want:4
4 will be order
# true or false conditionals

pizza_type=input('"a" for supreme or "b" for veggie special: ')

if pizza_type.lower()=="a":
    pizza_topping=input('"c" for pepperoni or "d" for mushroom: ' )
    
if pizza_topping.lower()=="c":
    print("here is your pepperoni supreme pizza")
else:
    if pizza_topping.lower()=="d":
        print("here is your mushroom supreme pizza")
        
if pizza_type.lower()=="b":
    pizza_topping=input('"e" for sweet veggie or "f" for regular veggie:')
    
if pizza_topping.lower()=="e":
    print("here is your sweet veggie pizza")
else:
    if pizza_topping.lower()=="f":
        print("here is your regular veggie pizza")
"a" for supreme or "b" for veggie special: a
"c" for pepperoni or "d" for mushroom: c
here is your pepperoni supreme pizza
# comparison operators

4>5
False
4<5
True
3<=5
True
3>=5
False
5>=5
True
x=3
x==9
False
d=3
x==d
True
x = 21
if x > 25:
    print("x is already bigger than 25")
else:
    print("x isn't bigger than 25")
    
x isn't bigger than 25
x = 26
if x > 25:
    print("x is already bigger than 25")
else:
    print("x was", x)
    x = 25
    print("now x is", x)
x is already bigger than 25
x = 19
if x + 18 == x + x:
    print("Pass: x + 18 is equal to", x + x)
else:
    print("Fail: x + 18 is not equal to", x + x)
Fail: x + 18 is not equal to 38
x = 45
test_value = 45
if x != test_value:
    print('x is not', test_value)
else:
    print('x is', test_value)
x is 45
# string comparison

"hello" < "Hello"
False
"aardvark" > "Zebra"
True
'student' != 'Student'
True
msg = "Save the notebook"

if msg.lower() == "save the notebook":
    print("message as expected")
else:
    print("message not as expected")
message as expected
msg = "Save the notebook"
prediction = "save the notebook"

if msg.lower() == prediction.upper():
    print("message as expected")
else:
    print("message not as expected")
message not as expected
# conditional

weather = input("Enter weather (sunny, rainy, snowy): ") 

if weather.lower() == "sunny":
    print("Wear a t-shirt")
elif weather.lower() == "rainy":
    print("Bring an umbrella and boots")
elif weather.lower() == "snowy":
    print("Wear a warm coat and hat")
else:
    print("Sorry, not sure what to suggest for", weather)
Enter weather (sunny, rainy, snowy): sunny
Wear a t-shirt
secret_num = "2"

guess = input("Enter a guess for the secret number (1-3): ")

if guess.isdigit() == False:
    print("Invalid: guess should only use digits")
elif guess == "1":
    print("Guess is too low")
elif guess == secret_num:
    print("Guess is right")
elif guess == "3":
    print("Guess is too high")
else:
    print(guess, "is not a valid guess (1-3)")
Enter a guess for the secret number (1-3): 2
Guess is right
# casting with int() & str ()

weight1 = '60' 
weight2 = 170 

total_weight = int(weight1) + weight2
print(total_weight)
230
num_1 = '11'
num_2 =  '15'
num_3 = 10

total_number = str(num_3)+num_1+num_2
print(total_number)
101115
# input str cast to int

student_age = input('enter student age (integer): ')
age_next_year = int(student_age) + 1
print('Next year student will be',age_next_year)
enter student age (integer): 5
Next year student will be 6
student_age = str(input('enter student age (string): '))

age_in_decade = student_age + '5'

print('In a decade the student will be', age_in_decade)
enter student age (string): '45'
In a decade the student will be '45'5
# math operator

def million_maker():
    make_big = input("enter a non-decimal number you wish were bigger: ")
    return int(make_big)*1000000

print("Now you have", million_maker())
enter a non-decimal number you wish were bigger: 0
Now you have 0
# nested conditionals

print("Hi, welcome to the sandwich shop.  Please select a sandwich.")
sandwich_type = input('"c" for Cheese or "v" for Veggie Special: ')

    
if sandwich_type.lower() == "c":
    
    print("Please select a cheese.")
    cheese_type = input('"c" for Cheddar or "m" for Manchego: ')
    print()
    
    if cheese_type.lower() == "c":
        print("Here is your Cheddar Cheese sandwich.  Thank you.")
    elif cheese_type.lower() == "m":
        print("Here is your Manchego Cheese sandwich.  Thank you.") 
    else:
        print("Sorry, we don't have", cheese_type, "choice today.")

elif sandwich_type.lower() == "v":
    print("Here is your Veggie Special. Thank you.")
        
else:
    print("Sorry, we don't have", sandwich_type, "choice today.")
print()
print("Goodbye!")
Hi, welcome to the sandwich shop.  Please select a sandwich.
"c" for Cheese or "v" for Veggie Special: c
Please select a cheese.
"c" for Cheddar or "m" for Manchego: m

Here is your Manchego Cheese sandwich.  Thank you.

Goodbye!
# nested condiionals escape sequence

student_age = 17
student_name = "Hiroto Yamaguchi"
print("STUDENT NAME\t\tAGE")
print(student_name,'\t' + str(student_age))
STUDENT NAME		AGE
Hiroto Yamaguchi 	17
print('Hello World!\nI am formatting print ')
Hello World!
I am formatting print 
print("\"quotes in quotes\"")
print("I\'ve said \"save your notebook,\" so let\'s do it!")


print("for a newline use \\n")
"quotes in quotes"
I've said "save your notebook," so let's do it!
for a newline use \n
# while true loop

number_guess = "0"
secret_number = "5"

while True:
    number_guess = input("guess the number 1 to 5: ")
    if number_guess == secret_number:
        print("Yes", number_guess,"is correct!\n")
        break
    else:
        print(number_guess,"is incorrect\n")
guess the number 1 to 5: 4
4 is incorrect

guess the number 1 to 5: 5
Yes 5 is correct!

seat_count = 0
soft_seats = 0
hard_seats = 0
num_seats = 4


while True:
    seat_type = input('enter seat type of "hard","soft" or "exit" (to finish): ')
    
    if seat_type.lower().startswith("e"):
        print()
        break
    elif seat_type.lower() == "hard":
        hard_seats += 1
    elif seat_type.lower() == "soft":
        soft_seats += 1
    else:
        print("invalid entry: counted as hard")
        hard_seats += 1  
    seat_count += 1
    if seat_count >= num_seats:
        print("\nseats are full")
        break
        
print(seat_count,"Seats Total: ",hard_seats,"hard and",soft_seats,"soft" )
enter seat type of "hard","soft" or "exit" (to finish): 1
invalid entry: counted as hard
enter seat type of "hard","soft" or "exit" (to finish): hard
enter seat type of "hard","soft" or "exit" (to finish): exit

2 Seats Total:  2 hard and 0 soft
student_fname = ""
while student_fname.isalpha() == False:
    student_fname = input("enter student\'s first (Letters only, No spaces): ")
print("\n" + student_fname.title(),"has been entered as first name")
enter student's first (Letters only, No spaces): jason

Jason has been entered as first name
# operation with numbers 

21*21.5
451.5
21/3
7.0
21//3
7
21//3.2
6.0
21%4
1
21%4.4
3.3999999999999986
21**4
194481
21**4.4
657301.913883832
# indexing
x='i like us to visit your favorite museum'
x[0]
x[2]
x[7]
x[13]
x[21]
'u'
a=x[0]
b=x[2]
c=x[7]
d=x[13]
e=x[21]
print(a+ b+c+d+e)
iluvu
print(x[0]+ x[2]+x[7]+x[13] +x[21])
iluvu
# slicing

x='i like us to visit your favorite museum'

y=x[0:9]

print(y)

    
i like us
# find location in sting

x.find('your')
19
#find id location 

print(id(x),id(y))
139879002757584 139879000108016
# logic operators

x=6
y=9
print (x>2 and y>2)
True
print(x>2 and y <2)
False
print(x>2 or y>2)
True
print(x>2 or y<2)
True
print(not(x>2 or y>2))
False
print(not(x>2 and y<2))
True
# assignments

p=5
x=p + 9

print (x)
14
a,b= 4,5

print(a,b)
4 5
c= 5
c,d =45,c
print(c,d)
45 5
x=9
x+= 5
print(x)
14
# if operator statement

x = int (input("Enter an interger days in year: "))
y = int (input("Enter an second interger days from last service: "))
if x-y >=0:
    print(x,"application accepted",y)
else:
    print(x, " application not accepted service date needs to be updated",y)
Enter an interger days in year: 364
Enter an second interger days from last service: 300
364 application accepted 300
# if operator statement program block

purchase_price= float (input("Enter the purchase price of the stock: "))
price_now=float (input("Enter the current price of the stock: "))
if price_now < purchase_price * 0.9:
    print("stop loss: sell the stock !")
    print("you've lost ", purchase_price-price_now,"dollars per share")
elif price_now > purchase_price *1.2:
    print("profit taking : don't sell the stock")
    print("you've gain", purchase_price-price_now,"dollars per share")
else:
    print("hold don't do anything")
    print("your unrealized profit is",purchase_price-price_now,"dollars per share")
Enter the purchase price of the stock: 8
Enter the current price of the stock: 9
hold don't do anything
your unrealized profit is -1.0 dollars per share
# indenting if operator statement nested block 

purchase_price= float (input("purchase price?"))
price_now= float (input("price now?"))
days_held=int (input("number of days position held?"))
if price_now <.9 * purchase_price:
    if days_held<10:
        if price_now <.8 * purchase_price:
            print("stop loss activated,close the position")
        else:
            print("do nothing")
    else:
        print("stop loss activated,positon should be close")
elif price_now >1.1 * purchase_price:
    print("profit taking,keep position open")
else:
    print("do nothing")
            
purchase price?8
price now?16
number of days position held?7
profit taking,keep position open
# calling a function ; black box ;

x=20
y=11
z=max(x,y)
print(z)
20
# none return

def spam(x):
    x=x+1
print(spam(5))
None
# multiple returns

def minmax(x,y):
    return min(x,y),max(x,y)
x,y= minmax(7,2)
print(x,y)
2 7
# passing agruments to a function

def div(x,y):
    return x/y
a=30
print(div(a,10))
3.0
#first order function

def order_by(a,b,order):
    return order(a,b)
order_by(4,7,max)
7
# list sequence order 

x=[4,5,6,7]
y=[]

print (x)
print (y)
[4, 5, 6, 7]
[]
# inserting items into a list

x=[2,4]
x.insert(0,'half')
print (x)
['half', 2, 4]
# adding items to a list
x=[]
x.append('one')
x.append('two')
print (x)
['one', 'two']
# unpacking a list
# += extends a viarable

X=[]
x.extend ([1,2,3])
print (x)
['one', 'two', 1, 2, 3]
# removing items from a list
# pop ; location
# remove ; specific item


x=[1,2,3,4,5,6,7,8,9]
x.pop()
print (x)
x.pop(3)
print (x)
x.remove(7)
print (x)
[1, 2, 3, 4, 5, 6, 7, 8]
[1, 2, 3, 5, 6, 7, 8]
[1, 2, 3, 5, 6, 8]
# mutable list

x=[1,2,3,4]
x[0]=8
print(x)
[8, 2, 3, 4]
# gotcha list
# mutable vs immutable

def eggs(item,total=0):
    total+=item
    return total

def spam (elem,some_list=[]):
    some_list.append(elem)
    return some_list
print(eggs(1))
print(eggs(2))
1
2
print(spam(1))
print(spam(2))
[1]
[1, 2]
# range iteration
x=[1,2,3,4,5,6,7,8,9,]
for index in range (len(x)):
    print(index,x[index])
    
0 1
1 2
2 3
3 4
4 5
5 6
6 7
7 8
8 9
list(range(len(x)))
[0, 1, 2, 3, 4, 5, 6, 7, 8]
x=9,8,7,6,5,4,3,2,1
for element in x:
    print(element)
9
8
7
6
5
4
3
2
1
def search_list(list_of_tuples,value):
    for element in list_of_tuples:
        if element [0] == value:
            return element[1]
prices=[('aapl',45.98),('ion',55.45),('gs',25.95) ]
ticker='google'
print(search_list(prices,ticker))
None
# dictionary :key value pair {}
mktcap={'aapl':45.9,'ion':55.4,'gs':25.9}
mktcap['gs']
25.9
# add key to dictionary
mktcap['google']=99.9
print(mktcap)
{'google': 99.9, 'gs': 25.9, 'ion': 55.4, 'aapl': 45.9}
# remove a key from dictionary

del(mktcap['google'])
print(mktcap)
{'gs': 25.9, 'ion': 55.4, 'aapl': 45.9}
mktcap.keys()
dict_keys(['gs', 'ion', 'aapl'])
sorted(mktcap.keys())
['aapl', 'gs', 'ion']
for key in mktcap:
    print(mktcap[key])
25.9
55.4
45.9
# set : unorder collection of unique objects

tickers={"aapl","gs","ion"}
"aapl" in tickers
True
# date time libary

d1="10/24/2017"
d2="10/24/2016"
max(d1,d2)
'10/24/2017'
student_name ="cipher"
print (student_name [4])
e
student_name ="cipher"
student_name ="todd"
if student_name[0].upper() =="c":
    print('Winner! Name starts with c:',student_name)
elif student_name[0].lower() =="j":
    print('Winner! Name starts with j:',student_name)
else:
    print('not a match,try again tomorrow:',student_name)
not a match,try again tomorrow: todd
#access sub_string by step size

student_name="cipher"
# print(student_name[:])
# print(student_name,"\n")
# print(student_name)
# print(student_name[::2])
print(student_name[1::2])
ihr
#iteration using for & in
word = "cello"

for letter in word:
    print(letter)
c
e
l
l
o
student_name ="SKye"
new_name = ""

for ltr in student_name:
    if ltr.lower() =="y":
        new_name += ltr.upper()
    else:
        new_name += ltr
        
print(student_name,"to",new_name)
SKye to SKYe
#return string information

work_tip ="save your code"

print("number of characters in string")
len(work_tip)
number of characters in string
14
#appending a value in a list
simple_list =[1,2,3,4]
print("simple_list before:", simple_list)

simple_list.append(3)
print("\nsimple_list after: ",simple_list)
simple_list before: [1, 2, 3, 4]

simple_list after:  [1, 2, 3, 4, 3]
#insert a new value for a index
party_list =["joana","fred","tod"]
print("party_list before:", party_list,"\n")

party_list[1] = "collete"

print("party_list after: ",party_list,"\n")
party_list before: ['joana', 'fred', 'tod'] 

party_list after:  ['joana', 'collete', 'tod'] 

party_list =["joana","fred","tod"]
print("before:",party_list,"\n")

party_list[1]= party_list[1] + ",collete"

print("after:",party_list)
before: ['joana', 'fred', 'tod'] 

after: ['joana', 'fred,collete', 'tod']
party_list = ["tod","fred","tim"]
print("party_list before: ",party_list)

print("index 1 is",party_list[1])
print("index 2 is",party_list[2],"\n")
party_list before:  ['tod', 'fred', 'tim']
index 1 is fred
index 2 is tim 

# delete a specific list index
sample_list =[11,35,85,62]
print("sample_list before: ")

import numpy as np
import numpy as np
# creating a numpy array
ax = np.array([1,2,3,4,5])
print(ax,id(ax),len(ax))
[1 2 3 4 5] 210000976 5
x=['1','2','3']
xi = np.array (x,'int')
xf = np.array (x,'float')
xs = np.array (x,'str')
print(xi,xf,xs,sep='\n')
[1 2 3]
[1. 2. 3.]
['1' '2' '3']
x = np.array([13,24,21.2,17.6,21.7],'float')
print(x.sum(),x.mean(),x.std(),sep='\n')
97.50000000000001
19.500000000000004
3.8429155598321434
x=[[0,1,2,3,4,5,],[10,11,12,13,14,15,],[20,21,22,23,24,25]]
ax=np.array(x,float)
print(ax)
[[ 0.  1.  2.  3.  4.  5.]
 [10. 11. 12. 13. 14. 15.]
 [20. 21. 22. 23. 24. 25.]]
# indexing array
ax[1,3]
13.0
#slicing array
ax[1:3,2:4]
array([[12., 13.],
       [22., 23.]])
#reshaping array
print(ax.shape)
ax.reshape(9,2)
(3, 6)
array([[ 0.,  1.],
       [ 2.,  3.],
       [ 4.,  5.],
       [10., 11.],
       [12., 13.],
       [14., 15.],
       [20., 21.],
       [22., 23.],
       [24., 25.]])
# creating initialized arrays
ax=np.arange(10)
print(ax)
ay=np.array([np.arange(2,10,2),np.arange(10)])
print(ay)
[0 1 2 3 4 5 6 7 8 9]
[array([2, 4, 6, 8]) array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])]
ax=np.ones(10)
print(ax)
[1. 1. 1. 1. 1. 1. 1. 1. 1. 1.]
ax =np.arange(10)**2
print(ax)
[ 0  1  4  9 16 25 36 49 64 81]
np.identity(10)
array([[1., 0., 0., 0., 0., 0., 0., 0., 0., 0.],
       [0., 1., 0., 0., 0., 0., 0., 0., 0., 0.],
       [0., 0., 1., 0., 0., 0., 0., 0., 0., 0.],
       [0., 0., 0., 1., 0., 0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 1., 0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0., 1., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0., 0., 1., 0., 0., 0.],
       [0., 0., 0., 0., 0., 0., 0., 1., 0., 0.],
       [0., 0., 0., 0., 0., 0., 0., 0., 1., 0.],
       [0., 0., 0., 0., 0., 0., 0., 0., 0., 1.]])
# matrix multiplications
ax = np.arange(10)
ay = np.array([ax,ax])
ay *2
array([[ 0,  2,  4,  6,  8, 10, 12, 14, 16, 18],
       [ 0,  2,  4,  6,  8, 10, 12, 14, 16, 18]])
ay.shape
(2, 10)
np.dot(ay,ay.reshape(10,2))
array([[220, 265],
       [220, 265]])
#comparing numphy array with lists
n=10
ax=np.array([np.arange(n)**2,np.arange(n)**3])
print(ax)
ay=ax.transpose()
np.dot(ax,ay)
[[  0   1   4   9  16  25  36  49  64  81]
 [  0   1   8  27  64 125 216 343 512 729]]
array([[ 15333, 120825],
       [120825, 978405]], dtype=int32)
# functionalize this
​
def dotproduct(n):
    ax=np.array([np.arange(n)**2,np.arange(n)**3])
    ay=ax.transpose()
    import datetime
    start = datetime.datetime.now()
    np.dot(ax,ay)
    end = datetime.datetime.now()
    return end-start
​
dotproduct(10)
​
​
datetime.timedelta(0)
# do the same with python list
def dot_product_list(n):
    x= [x**2 for x in range (n)]
    y= [x**3 for x in range (n)]
    ax =[x,y]
    ay =[list(i)for i in zip(*ax)]
    import datetime
    start = datetime.datetime.now()
    [[sum(a*b for a,b in zip(x_row,y_col)) for y_col in zip (*ay)] for x_row in ax]
    end = datetime.datetime.now()
    return end-start
​
dot_product_list(10000)
datetime.timedelta(microseconds=42430)
for n in [10,100,1000,1000]:
    numpy_result=dotproduct(n)
    list_result=dot_product_list(n)
    print(n,numpy_result,list_result,sep='\t')
10	0:00:00	0:00:00
100	0:00:00	0:00:00
1000	0:00:00.003994	0:00:00.003994
1000	0:00:00	0:00:00.003988
#selecting elements from an array
x=[[0,1,2,3,4,5],[10,11,12,1,14,15],[20,21,22,23,24,25]]
ax=np.array(x,float)
np.where(ax%2==0,1,0)
array([[1, 0, 1, 0, 1, 0],
       [1, 0, 1, 0, 1, 0],
       [1, 0, 1, 0, 1, 0]])
import scipy
scipy.nanmean(x)
11.833333333333334
#random number support in numpy
np.random.normal(size=10)
np.random.normal(size=(100,100))
np.random.exponential()
np.random.exponential(1.0,size=(6,3))
np.random.randint(-10,10,size=(9,9))
array([[ -6,   3,  -4,  -4,  -9,  -6,   4,  -2,   5],
       [  9,  -8, -10,  -6, -10,   9,   8,  -9,   2],
       [ -3,  -5,   8,   0,  -3,   5,   5,  -4,  -7],
       [  9,  -6,   2,   5,  -1,   5, -10,  -8,   4],
       [ -5,  -4,  -8,  -8,   2, -10,  -9,  -4,   8],
       [  2, -10,   7,   6,   1,  -6,   9,  -5,   0],
       [ -8,   4,   6,   9,   7,   6,  -8,   8,  -7],
       [  6,   5,   4,  -4,   7,   6,  -2,  -8,  -8],
       [  8,   7,   6,  -4,  -6,  -4,   4,   2,   1]])
import pandas as pd
from pandas_datareader import data
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
import datetime as dt
# the structure of dataframe
pd.DataFrame([[1,2,3],[1,2,3]],columns=['A','B','C'])
A	B	C
0	1	2	3
1	1	2	3
#accessing columns and rows
df=pd.DataFrame([['r1','00','01','02'],['r2','10','11','12'],['r3','20','21','22']],columns=['row_label','A','B','C'])
print(id(df))
print (df)
df.set_index('row_label',inplace=True)
print(id(df))
df
278372464
  row_label   A   B   C
0        r1  00  01  02
1        r2  10  11  12
2        r3  20  21  22
278372464
A	B	C
row_label			
r1	00	01	02
r2	10	11	12
r3	20	21	22
#getting colums data
df['B']
row_label
r1    01
r2    11
r3    21
Name: B, dtype: object
#getting row data
df.loc['r1']
A    00
B    01
C    02
Name: r1, dtype: object
#getting a row by row number
df.iloc[1]
A    10
B    11
C    12
Name: r2, dtype: object
#getting multiple columns
df[['A','B']]
​
A	B
row_label		
r1	00	01
r2	10	11
r3	20	21
#getting a specific cell
df.loc['r2']['A']
'10'
#slicing
df.loc['r1':'r2']
A	B	C
row_label			
r1	00	01	02
r2	10	11	12
df.loc['r1':'r2','B':'C']
B	C
row_label		
r1	01	02
r2	11	12
import networkx as nx
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
#constructing a simple network
simple_network = nx.Graph()
nodes = [1,2,3,4,5,6,7,8]
edges = [(1,2),(2,3),(1,3),(4,5),(2,7),(1,9),(3,4),(4,5),(4,9),(5,6),(7,8),(8,9)]
simple_network.add_nodes_from(nodes)
simple_network.add_edges_from(edges)
nx.draw(simple_network)

#add labels to the nodes
pos=nx.spring_layout(simple_network)
​
nx.draw_networkx_nodes(simple_network,pos,
                        node_color='r',
                        node_size=500,
                       alpha=0.8)
​
nx.draw_networkx_edges(simple_network,pos,
                       edgelist=edges,
                       width=8,alpha=0.5,edge_color='b')
​
node_name={}
for node in simple_network.nodes():
    node_name[node]=str(node)
    
nx.draw_networkx_labels(simple_network,pos,node_name,font_size=16)
​
plt.axis('off')
plt.show()
    

#simple querries on a network
​
#simple_network.has_edge(2,9)
#simple_network.has_node(2)
#simple_network.number_of_edges()
#simple_network.number_of_nodes()
#simple_network.order()
#len (simple_network)
#iterating over a network
for n in simple_network.nodes():
    print(n)
1
2
3
4
5
6
7
8
9
for a in simple_network.adjacency():
    print(a)
(1, {2: {}, 3: {}, 9: {}})
(2, {1: {}, 3: {}, 7: {}})
(3, {2: {}, 1: {}, 4: {}})
(4, {5: {}, 3: {}, 9: {}})
(5, {4: {}, 6: {}})
(6, {5: {}})
(7, {2: {}, 8: {}})
(8, {7: {}, 9: {}})
(9, {1: {}, 4: {}, 8: {}})
for e in simple_network.edges():
    print(e)
(1, 2)
(1, 3)
(1, 9)
(2, 3)
(2, 7)
(3, 4)
(4, 5)
(4, 9)
(5, 6)
(7, 8)
(8, 9)
for d in simple_network.degree():
    print(d)
(1, 3)
(2, 3)
(3, 3)
(4, 3)
(5, 2)
(6, 1)
(7, 2)
(8, 2)
(9, 3)
print(nx.shortest_path(simple_network,6,8))
​
[6, 5, 4, 9, 8]
#insert items into a list
party_list=["joana","tommy","kate"]
print("party_list before: ",party_list)
​
print("index 1 is",party_list[1])
print("index 2 is",party_list[0], "\n")
party_list before:  ['joana', 'tommy', 'kate']
index 1 is tommy
index 2 is joana 

party_list.insert(1,"colette")
​
print("party_list after: ", party_list)
print("index 1 is",party_list[1], "\nindex 2 is", party_list[2],"\nindex 3 is", party_list[3])
party_list after:  ['joana', 'colette', 'tommy', 'kate']
index 1 is colette 
index 2 is tommy 
index 3 is kate
#delete a specific list index
sample_list=[11,24,46,83,99]
​
del sample_list[0]
print("sample_list after: ",sample_list)
sample_list after:  [24, 46, 83, 99]
#.pop()get and delete item from a list
number_list =[1,2,3,4,5]
print("number_list before: ",number_list, "\n")
​
number_list.pop(2)
print("number_list after: ", number_list ,"\n")
number_list before:  [1, 2, 3, 4, 5] 

number_list after:  [1, 2, 4, 5] 

#while'empty list' evaluates' as false
dog_type = ["lab","pug","poodle"]
print(dog_type,"\n")
​
while dog_type:
    print(dog_type.pop(),"popped , list now = ",dog_type)
​
​
['lab', 'pug', 'poodle'] 

poodle popped , list now =  ['lab', 'pug']
pug popped , list now =  ['lab']
lab popped , list now =  []
#delete a specific object from list with .remove()
dog_type =["lab","pug","poodle"]
​
if "cat" in dog_type:
    dog_type.remove("cat")
else:
    print("no pug found")
    
print(dog_type,"\n")
no pug found
['lab', 'pug', 'poodle'] 

# iterate through list
cities = ["new york","miami","orlando","atlanta","jacksonville"]
​
for cities in cities:
    print(cities)
new york
miami
orlando
atlanta
jacksonville
sales =[2,4,5,6,7,8,9]
total=10
​
for sales in sales:
    total += sales
    
print("total sales",total)
total sales 51
#sort and filter
foot_bones=["calcaneus","talus","cuboid","navicular","laternal cuniform","intermidiate cuniform"]
​
longer_names=""
shorter_names=""
​
for bone_name in foot_bones:
    if len(bone_name)< 8:
        shorter_names += bone_name +"\n"
    else:
        longer_names += bone_name +"\n" 
        
print("short name :\n "+ shorter_names)
print("long name : \n"+ longer_names )
​
short name :
 talus
cuboid

long name : 
calcaneus
navicular
laternal cuniform
intermidiate cuniform

# count and search
cities = ["new york","jersey","atlanta","antractica","kentucky"]
search_letter="a"
total=0
​
for city_name in cities:
    total +=city_name.lower().count(search_letter)
​
print(cities)
    
print("the total # of\" "+ search_letter +"\"found in the list is",total)
​
['new york', 'jersey', 'atlanta', 'antractica', 'kentucky']
the total # of" a"found in the list is 6
#range(stop)
digits = range(10)
print("digits =",list(digits),"\n")
sub_total=0
​
for item in digits:
    sub_total += item
    print("sub_total:",sub_total)
print("Total=",sub_total)
    
digits = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] 

sub_total: 0
sub_total: 1
sub_total: 3
sub_total: 6
sub_total: 10
sub_total: 15
sub_total: 21
sub_total: 28
sub_total: 36
sub_total: 45
Total= 45
# range use in iteration list
spell_list = ["tuesday","wednesday","friday","october","december","annual","calendar"]
​
half_1=int(len(spell_list)/2)
print("half way =",half_1,"\n")
​
for word in range(half_1):
    print(spell_list[word])
half way = 3 

tuesday
wednesday
friday
#range start/stop
​
sub_total = 0
temp = 0
​
for item in range(5, 11):
    temp=sub_total
    sub_total += item
    print("sub_total:",temp,"+",item,"+",sub_total)
​
print("Total =",sub_total)
sub_total: 0 + 5 + 5
sub_total: 5 + 6 + 11
sub_total: 11 + 7 + 18
sub_total: 18 + 8 + 26
sub_total: 26 + 9 + 35
sub_total: 35 + 10 + 45
Total = 45
#range start/stop/step
​
total=0
​
for item in range(25,46,5):
    print(item)
    total+= item
print("Total =",total)
25
30
35
40
45
Total = 175
#printing the first and every other word
spell_list =["monday","tuesday","wednesday","thursday"]
​
for index in range(0,len(spell_list),2):
    print(spell_list[index])
    
monday
wednesday
#combine list
visited_cities =["new york","jersey","florida","georgia"]
wish_cities =["tokyo","bangkok","china","india"]
​
all_cities=visited_cities+wish_cities
print("all cities")
​
for city in all_cities:
    print(city)
​
all cities
new york
jersey
florida
georgia
tokyo
bangkok
china
india
#extend list
visted_cities=["new york","jersey","florida","georgia"]
wish_cities=["tokyo","bangkok","china","india"]
​
visted_cities.extend(wish_cities)
print("all cities",visted_cities)
all cities ['new york', 'jersey', 'florida', 'georgia', 'tokyo', 'bangkok', 'china', 'india']
#reverse a list
cities_1=["new york","jersey","florida","georgia"]
​
print("initial order",cities_1)
cities_1.reverse()
​
print("reverse order",cities_1)
​
initial order ['new york', 'jersey', 'florida', 'georgia']
reverse order ['georgia', 'florida', 'jersey', 'new york']
#list sort
quiz_score =[20,10,5,20,17,9,10]
print("initial quiz score:",quiz_score)
​
quiz_score.sort()
​
print("sorted quiz score:",quiz_score)
​
initial quiz score: [20, 10, 5, 20, 17, 9, 10]
sorted quiz score: [5, 9, 10, 10, 17, 20, 20]
#list sorted
game_point =[20,10,5,17,3]
​
sorted_point = sorted(game_point)
​
print("game_points list: ",game_point)
print("sorted_points list:",sorted_point)
game_points list:  [20, 10, 5, 17, 3]
sorted_points list: [3, 5, 10, 17, 20]
#converting a string to a list with .split()
rhyme= "London bridge is falling down"
rhyme_word=rhyme.split()
print(rhyme_word)
​
rhyme_word.reverse()
​
for word in rhyme_word:
    print(word)
​
print(rhyme_word)
['London', 'bridge', 'is', 'falling', 'down']
down
falling
is
bridge
London
['down', 'falling', 'is', 'bridge', 'London']
tip ="notebook can be exported as pdf"
tip_word=tip.split()
​
print("string:",tip)
print("list:",tip_word,"\n")
​
for word in tip_word:
    print(word)
string: notebook can be exported as pdf
list: ['notebook', 'can', 'be', 'exported', 'as', 'pdf'] 

notebook
can
be
exported
as
pdf
#set split character
tip ='Python_uses_space_for_indentation'
tip_words = tip.split('_')
​
print(tip_words)
['Python', 'uses', 'space', 'for', 'indentation']
tip="python uses space for indentation"
tip_words =tip.split("a")
​
print(tip)
print(tip_words)
python uses space for indentation
['python uses sp', 'ce for indent', 'tion']
#.join() method
no_space=""
letters =["p","y","t","o","n"]
​
print(no_space.join(letters))
pyton
!curl https://raw.githubusercontent.com/MicrosoftLearning/intropython/master/poem1.txt -o poem1.txt
    
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed

  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
100    56  100    56    0     0     54      0  0:00:01  0:00:01 --:--:--    54
poem_file=open ('poem1.txt','r')
poem_file
<_io.TextIOWrapper name='poem1.txt' mode='r' encoding='cp1252'>
 !curl https://raw.githubusercontent.com/MicrosoftLearning/intropython/master/world_temp_mean.csv -o mean_temp.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed

  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0
100   222  100   222    0     0     67      0  0:00:03  0:00:03 --:--:--    67
100   222  100   222    0     0     67      0  0:00:03  0:00:03 --:--:--    67
mean_temps = open("mean_temp.txt",'r')
print("\n\n"+ mean_temps.read())


city,country,month ave: highest high,month ave: lowest low
Beijing,China,30.9,-8.4
Cairo,Egypt,34.7,1.2
London,UK,23.5,2.1
Nairobi,Kenya,26.3,10.5
New York City,USA,28.9,-2.8
Sydney,Australia,26.5,8.7
Tokyo,Japan,30.8,0.9

# getting started 
# x+16=-25
# x +16-16=-25-16
x=-25-16
print(x)
-41
