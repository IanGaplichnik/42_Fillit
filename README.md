# 42_FILLIT

Aim of this project is to read a file, check it for errors (e.g. invalid input), determine the shapes, entered by the user, and insert those shapes in the smallest square possible.
Top-left corner is prioritized and pieces are entered in the order of appearence in the file.
&nbsp;
&nbsp;

### Compiling
---
Running ```make``` command will create a ```fillit``` executable.
```make clean``` will delete object files and ```make fclean``` deletes object files and executable.
&nbsp;
&nbsp;

### Running the program
---
After compiling the executable (see above), you can execute it by running:
```./fillit maps/%map_name%```.
Running invalid maps will output an error message to the standart output and valid ones will output the solution.
&nbsp;
&nbsp;

#### Example
---
Running map
```
....
..##
.##.
....

.##.
..#.
..#.
....

##..
##..
....
....

...#
..##
..#.
....

....
...#
..##
...# 
```
will create next output:
````
.AABB
AA.DB
.EDDB
EEDCC
.E.CC
````

Where letters represent the piece, in the appearance order in the file.
