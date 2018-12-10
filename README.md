print("Hello, World!");<br/>
if 5>7:<br/>
    print ("5 is more than 2");<br/>
else:<br/>
    print (" 2 is more than 5");<br/>
    <br/>
x=10;<br/>
y=10;<br/>
<br/>
z=x+y;<br/>
<br/>
print( str(x) +" + " + str(y) +"="+ str(z));<br/>
<br/>
x = 1    # int<br/>
y = 2.8  # float<br/>
z = 1j   # complex<br/>
print(type(x));<br/>
print(type(y));<br/>
print(type(z));<br/>
<br/>
x = 1.10<br/>
y = 1.0<br/>
z = -35.59<br/>
<br/>
print(type(x));<br/>
print(type(y));<br/>
print(type(z));<br/>
<br/>
a = "Hello, World!";<br/>
print(a[1]);<br/>
<br/>
b = "Hello, World!";<br/>
print(b[2:5]);<br/>
<br/>
<br/>
a = " Hello, World! "<br/>
print(a.strip()) # returns "Hello, World!" <br/>
<br/>
a = "Hello, World!"<br/>
print(len(a))<br/>
<br/>
a = "Hello, World!"<br/>
print(a.lower())<br/>
<br/>
a = "Hello, World!"<br/>
print(a.upper())<br/>
<br/>
a = "Hello, World!"<br/>
print(a.replace("H", "J"))<br/>
<br/>
a = "Hello, World!"<br/>
print(a.split(",")) # returns ['Hello', ' World!'] <br/>
<br/>
# print("Enter your name:")<br/>
# x = input()<br/>
# print("Hello, " + x)<br/>
<br/>
print ( 10 * 5);<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
print(thislist);<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
print(thislist[1])<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
thislist[1] = "blackcurrant"<br/>
print(thislist)<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
for x in thislist:<br/>
  print(x) <br/>
  <br/>
  <br/>
  thislist = ["apple", "banana", "cherry"]<br/>
if "apple" in thislist:<br/>
  print("Yes, 'apple' is in the fruits list") <br/>
  <br/>
  <br/>
  thislist = ["apple", "banana", "cherry"]<br/>
print(len(thislist))<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
thislist.append("orange")<br/>
print(thislist)<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
thislist.insert(1, "orange")<br/>
print(thislist)<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
thislist.remove("banana")<br/>
print(thislist)<br/>
<br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
del thislist[0]<br/>
print(thislist)<br/>
<br/>
<br/>
# thislist = ["apple", "banana", "cherry"]<br/>
# del thislist<br/>
# print(thislist) #this will cause an error because "thislist" no longer exists. <br/>
<br/>
thislist = ["apple", "banana", "cherry"]<br/>
thislist.clear()<br/>
print(thislist)<br/>
