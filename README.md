# project by Alawi Hussein 101
I made this project you must read the comments and learn python.
The important thing to understand what are you doing,
and so you don't forget what you did, You must apply the written.
## 3 السوأل
### how to show a string and and show snake icon forever
```python
# show string "Hassan!"
basic.show_string("Hassan!")
# make a function called on_forever
def on_forever():
    basic.show_icon(IconNames.SNAKE)
# set the function on_forever to loop forever
basic.forever(on_forever)
```
## 4 السوأل
### how to make a random number between 0 and 10 everytime we shake the micro bit, and it show us a random number
```python
def on_gesture_shake():
    # basic show_number to show a number to the micro bit
    basic.show_number(randint(0, 10)) # randint means random int random number between 0 and 10
# set the function
input.on_gesture(Gesture.SHAKE, on_gesture_shake) #this to tell micro bit that when it get shake run the on_gesture_shake function
```
## 5 السوأل
### how to show a number and make a variable 'Myage'
```python
# create variable called 'Myage'
Myage = 17
# show a number to the micro bit
basic.show_number(Myage) # then we put 'Myage' inside parentheses brackets
```

## 6 السوأل
### how to make variable named 'Myname'
```python
# create variable called 'Myname'
Myname = 17
# show a string to the micro bit
basic.show_string(Myname) # then we put 'Myname' inside parentheses brackets so micro bit show us the reuaslt
```
