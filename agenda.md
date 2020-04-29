1. General info about what a Jupyter notebook ist
write some text
write some code
the fields are called cells
move cells around

Show lpj output analysis

show video in ndvi_bavaria/maisenlach.ipynb

2. Markdown
github readme is in markdown
heading
* bullet points
  * within bullet points
enumeration

quotes

> Two beers or not two beers

table


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | \$1600 |
| col 2 is      | centered      |   \$12 |
| zebra stripes | are neat      |    \$1 |

![caption](img/zoom_meeting.png)

code snippets with
```
```
latex
Let's write a formula: $\sum_{i=10}^\infty i = y$

$$
\sum_{i=0}^\infty q^i = \frac{1}{1-q} , \forall q \in [0, 1)
$$


See more at: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#videos


3. Kernels
dozens of kernels, need to manually install them
R kernel (3 commands in rstudio)
create r notebook (top left: PLUS sign --> new launcher)
data.frame(1, 2, 3)

4. Slides
Reveal.js --> in-browser slideset
directly export as slides --> everything in one slide
settings -> slide type

5. code
code completion
import numpy as np
import matplotlib.pyplot as plt
--> complete

plot stuff

import matplotlib.pyplot as plt
fig, ax = plt.subplots(1, 1, figsize=(10, 4))
x = range(0, 10)
plt.plot(x, np.sin(x))
ax.set_title('sinus, obviously :-P')
plt.show()

now add %matplotlib widget at the top

functions with parameter --> reusable code
%matplotlib inline

def plot_my_sinus(a):
    fig, ax = plt.subplots(1, 1, figsize=(10, 4))
    x = np.linspace(0, 10, 100)
    plt.plot(x, a * np.sin(x))
    plt.plot(x, np.sin(x))
    ax.set_title('sinus, obviously :-P')
    plt.show()

change  widget to inline

5. PDF
show template
show compile
show resulting PDF
table of contents
references: In section Nitrogen Cycle

5. TOC extension


6. citations

7. version control
save file
mess something up
commands -> revert to checkpoint

Introduction to version control

Git: make sure everything is nice, then commit everything, then do a text change
--> git status
change only text --> ok

change a p

8. Collaboration
mybinder.org
