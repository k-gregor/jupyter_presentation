1. General info about what a Jupyter notebook ist
write some text
write some code
the fields are called cells

2. Markdown
heading
bullet points
enumeration
table
image ![yo](img/wednesday.jpg)
code snippets with
```
```
latex
Let's write a formula: $\sum_{i=10}^\infty i = y$

$$
\sum_{i=0}^\infty q^i = \frac{1}{1-q} , \forall q \in [0, 1)
$$

3. Kernels
dozens of kernels, need to manually install them
R kernel (3 commands in rstudio)
create r notebook
data.frame(1, 2, 3)

4. Slides
Reveal.js --> in-browser slideset
directly export as slides --> everything in one slide
settings -> slide type

5. code
code completion
import pandas as pd
--> complete

functions with parameter --> reusable code
%matplotlib inline

def plot_my_sinus(a):
    fig, ax = plt.subplots(1, 1, figsize=(10, 4))
    x = np.linspace(0, 10, 100)
    plt.plot(x, a * np.sin(x))
    plt.plot(x, np.sin(x))
    ax.set_title('sinus, obviously :-P')
    plt.show()

5. Plots
Interactive Plots
%matplotlib widget
fig, ax = plt.subplots(1, 1, figsize=(10, 4))
x = range(0, 10)
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

Git: make sure everything is nice, then commit everything, then do a text change
--> git status
