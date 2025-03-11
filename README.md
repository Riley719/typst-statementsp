# statementsp
## Discription
This statementsp, the statement special package, enables you to make these boxes for some statement.

![sampleimage](images/sampleimage.jpg)

## How to use
At first, you need to write the following code in your main typst file.
<pre>
  #import "@preview/statementsp:0.1.0": *
  #show heading: reset-counter(statementnum, levels: 2)
</pre>
Then, there are 3 steps to make your own boxes.
### Step1: Set a newstatementsp function
If you want to make Def boxes as the above sample image, you need to use a newstatament function and ready to make boxes.
<pre>
  #newstatementsp("def", "Def", black, rgb("#FFCCCC"))
</pre>
First argument is a box name you use in typst script. Second is a strings displayed at boxes. If you set second argument "Special Definition", box will be made like this.

![Super Definition](images/superdefinition.jpg)
