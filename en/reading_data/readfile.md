
# Reading simple text files

### Exercise 1

Create a text file `bigbang.txt` in a text editor, containing the following data:

    Emily,F,12562
    Amy,F,2178
    Penny,F,342
    Bernadette,F,129
    Leonard,M,384
    Howard,M,208
    Sheldon,M,164
    Stuart,M,82
    Raj,M,41



## Exercise 1:

Make the program work by inserting `close`, `line`, `bigbang.txt`, `print` into the gaps.

    f = open(___)
    for ____ in f:
        ____(line)
    f.____()

#### Hint: 

Depending on your editor, you may need to insert the complete path to the file. If the program does not work, a wrong file name or location are the most probable reasons.


### Exercise 3

How many different *girls names* were there in 2015?

**Sort** the following code lines and **indent them correctly**:

    girls = 0

    if "B" in line:

    print(girls)

    if ",F," in line:

    for line in open('names/yob2015.txt'):

    girls += 1


### Exercise 4

Extend the program from the previous exercise such that boys and girls names are counted separately.


### Exercise 5

Which of the following commands are correct?

* `for char in "ABCD":`
* `for i in range(10):`
* `for number in [4, 6, 8]:`
* `for k in 3+7:`
* `for (i=0; i<10; i++):`
* `for var in open('bigbang.txt'):`


### Exercise 6

Write a program that reads lines from the file `yob2015.txt`. Identify all lines containing your name and print them to the screen.
