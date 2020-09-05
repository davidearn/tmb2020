# SOFTWARE

There are several software packages that you must have on your laptop for this course.
* LaTeX
* R (and the RStudio GUI for R)
* Emacs
* A spell-checker that understands LaTeX

### Learning R

[R](http://www.r-project.org) is an open-source programming language
that you can download and install on any computer.  Installing R gives
you the language interpreter and a simple interactive shell.
 
[RStudio](https://www.rstudio.com/products/rstudio/) is an integrated
development environment (IDE) for R. It includes a console,
syntax-highlighting editor that supports direct code execution, as
well as tools for plotting, history, debugging and workspace
management.

There will a very brief introduction to R in class.  There are many
ways to learn R more systematically online.  One possibility is
[DataCamp](https://www.datacamp.com/home).  They have previously
provided free access to students registered in my courses, but they
are currently (summer 2020) not responding to requests.  If you are
unfamiliar with R, a good way to start is probably by taking 4 hours
to work through DataCamp's
[Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r).
Another possibility is to work through Hadley Wickham's free online
book [R for Data Science](https://r4ds.had.co.nz/).

# LaTeX

The standard system for mathematical typesetting.  You must use it for
your assignments, final project and presentations.

There are several distributions of TeX but
[TeXLive](https://www.tug.org/texlive/) has the advantage of having
both Windows and OS X versions and including good TeX/LaTeX editors
(TeX is a typesetting program and does not itself include an editor).

## Installation & Configuration Notes for LaTeX

### Windows
* the installation can easily take 30 to 60 minutes
* just download and run the '''install-tl.exe''' file

### OS X
* [https://www.tug.org/mactex/ MacTeX] is a bundle of TeXLive plus
  TeXShop (a TeX editor that many people like) and a number of tools.

# Emacs

Emacs is a very powerful editor and can be used for - among other
things - R and LaTeX. The learning curve is a little bit steep, but
the payoff comes in efficiency.  Use is optional but encouraged.

## Installation & Configuration Notes for Emacs

### Windows
* make sure to run `bin/addpm` once in order to configure emacs and
  create an icon under the Start menu

### OS X

Aquamacs (http://aquamacs.org) is a good graphical version of Emacs
for OS X.  You can just also run the command ```emacs``` from a
Terminal or XQuartz window.

# Spell-checkers and word counters that understand LaTeX

There are a number of
[spell-checkers that understand LaTeX](http://en.wikibooks.org/wiki/LaTeX/Tips_and_Tricks#Spell-checking_and_Word_Counting),
for example:
* ispell
* aspell
* hunspell
All of these run on Macs via the Terminal.

The unix `wc` command can be used to count words in a plain text file.
To use it, you first need to remove the TeX macros from your file.
You can then pipe the output into `wc`.  For example, from the terminal
window on a Mac you can type ```detex <filename> | wc``` where you
need to insert the _filename_ of the file in question.

If you have a Mac, the `texcount` command is much more helpful than
the above.  The command line syntax is ```texcount filename```, after
which helpful information is spewed on your screen.

# Tools for online collaboration on documents and code

[GitHub](https://github.com/)
* collaboration on anything, with superb version control

[Dropbox](https://www.dropbox.com/)
* very simple and convenient, but less-than-superb version control

[Main page for this course](.)
