# xResume
This is my resume (and CV) in LaTeX


##Using XeLaTeX

XeLaTeX is a version of Latex with great font rendering fuctionality (unicode, bidi, special font features). Since my resume uses 'lower case numerals' it looks slightly better with XeLaTeX.

In recent Ubuntu versions you simply clone this project, change directory to the root of the project and do:

    sudo apt-get install texlive-xetex texlive-latex-recommended tex-gyre
    ./xelatex *-resume.pdf
If all went well an updated version of the PDF is found in your current working directory, alongside a bunch of .log and .aux files that you can safely ignore.

##FontAwesome

for icon on [fortawesome](http://fortawesome.github.io/Font-Awesome/icons/)

##licence

You are allowed to take my code whole-sale and produce your own resume. For obvious reasons you may not reuse any of the content (such as skills, etc) but do with the formatting as you will. If you use my source to build your resume, I would love a link to your resume to see what you did differently (usually better).


