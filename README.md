# VEB-Tree-Python

1) (Optional) Run create_test.py to create input.txt (input files) for testing. <br />
2) If you don't do step 1, delete all the lines below the VEB class. Those lines are for reading input files to test.

A Van Emde Boas tree written in python.
Support Predecessor, Successor, is_in, insert in log(log(u)) time, where u is around 2^(2^max_num_in_list)


## Documents
https://thuandchu-portfolio.herokuapp.com/veb/assets/player/KeynoteDHTMLPlayer.html#0

## How to use VEB.
**To use VEB, first,**
```
 v = VEB(u)
```
**To insert a number,simply**
```
  v.insert(x)
```

**To check if the number is in the VEB,**
```
 v.is_in(x)
```

**To find the Predecessor or Successor,**
```
 v.predecessor(x)
 v.successor(x)
```

**Where u is the approximate maximum number in your list.** <br />
**The VEB tree can do all the query in a rane [0,u-1].**

## Running time of VEB.
<img width="552" alt="screen shot 2016-10-15 at 1 28 03 am" src="https://cloud.githubusercontent.com/assets/17826527/19417383/b0315392-93ee-11e6-8388-1aa8eb41230e.png">
