# new-screen-setup
Just some things to quickly see screen dimensions and stuff when plugging in etc

## code width and font check

To see if current screen setting has enough code width, and using various characters whether it's fixed width.

tl;dr - if they don't all line up evenly, you're using a non-monospace font, and the code width numbers are embedded.

Here's what it looks like with code friendly monospace:

```
|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
(((((((((((((((((((((((((((((((((((((( ((((((((((((((((((((((((((((((((((((((( ((((((((((((((((((((((((((((((((((((((( (((((((((((((((((((((((((((((((
The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick br
iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiii
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
...................................... ....................................... ....................................... ...............................
12340123401234012340123401234012340123 012340123401234012340123401234012340123 012340123401234012340123401234012340123 0123401234012340123401234012340
llllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllll
LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL
|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
```

And here's whatever font you're reading this via github in:

|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
(((((((((((((((((((((((((((((((((((((( ((((((((((((((((((((((((((((((((((((((( ((((((((((((((((((((((((((((((((((((((( (((((((((((((((((((((((((((((((
The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick br
iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii iiiiiiiiiiiiiiiiiiiiiiiiiiiiiii
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
...................................... ....................................... ....................................... ...............................
12340123401234012340123401234012340123 012340123401234012340123401234012340123 012340123401234012340123401234012340123 0123401234012340123401234012340
llllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllllllllllll lllllllllllllllllllllllllllllll
LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL
|...|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|....|..
1   5    10   15   20   25   30   35   40   45   50   55   60   65   70   75   80   85   90   95   100  105  110  115  120  125  130  135  140  145  150
