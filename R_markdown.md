# Which R filetype to choose?

There are a number of different file types you can create in R Studio which will all run your analyses. These include basic `.r` files, R Markdown files and R Notebooks (both end `.Rmd`), and now Quarto files (ending in `.qmd`). While many people may prefer to run base `.r` files for various reasons, there are many benefits to using the other file types. The main reason is because all of the `.Rmd` and `.qmd` files allow you to combine Markdown and code in a single file. 

## What is markdown?

Markdown (i.e., the `md` part of the `.Rmd` and `.qmd` file extensions) is a simple text markup format. Basically, markdown lets you include some text but also style the text, such as **bolding**, *italicising*, creating headers, and so on. Markdown converts seamlessly to other formats, allowing documents to be created in html (for websites), but also as PDF or even Word formats. For example, you can easily convert your R Markdown to [custom styled Word documents](https://rmarkdown.rstudio.com/articles_docx.html). 

Markdown is thus not specific to R or R notebooks, but is a more universal method for rendering text that is employed in various different applications. That being said, [R Markdown does have its own set of formatting guidelines](Here is a [cheatsheet for R Markdown).

## Choosing R Markdown

R Markdown is a solid choice if you are only concerned with executing R code. There is very little difference between and R Markdown and an R Notebook ([in fact they are basically the same thing](https://stackoverflow.com/questions/43820483/difference-between-r-markdown-and-r-notebook)). The Quarto format is newer and is designed to be language agnostic, meaning it can work with Python, Julia, Javascript, and other programming langauges. Quarto also plays nice with R Studio's visual editor. However, there is no need or requirement to use Quarto if all you want to do is run some R. 

To keep things simple, all of the R files in this workshop will be basic R Markdown files (`.Rmd`). If you like to use Quarto instead, you should be able to easily convert between the two. 

