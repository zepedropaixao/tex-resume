[![Build Status](https://travis-ci.org/zepedropaixao/paixaocv.svg?branch=master)](https://travis-ci.org/zepedropaixao/paixaocv)

# My CV in TeX

XeLaTex implementation of my CV. 

The guidelines that led me to this CV design and layout were the following rules that I found in [this](https://www.quora.com/How-can-a-software-engineer-write-a-killer-resume/answer/Allen-Cheung?share=da9df56a&srid=JRMM) Quora answer and believe to be the current standard considerations in recruitment nowadays:

* **A single pager.** Unless you have two+ decades of experience you do not have enough interesting things to say on your resume, and I just won't read it. Include a github link or a personal site if you want to show off what you've done.
* **Projects, with technical implementation descriptions.** Recruiters look for keywords, engineers look for algorithms, techniques and niche software. "Wrote sorted hash map" is more interesting than "used jsonp for Javascript AJAX UI".
* **Technical proficiencies.** Listing the twenty languages you've used is pretty standard, but we both know that you'd be most comfortable with a small subset, so try to specify which those are. I don't do this, but some interviewers will pick an area that you've listed on your resume and deep dive on the nuance, and hold it against you when you flounder.
* **Post code online.** There's only so much you can get across in an interview setting (especially when accounting for nervousness, bad questions, scheduling, etc.), and I'm always looking for more evidence outside of the interview if you can provide it. You also get the benefit of having spent much more time & having had many more revisions for anything you post online.

## Clone this repository

First clone this repository in any folder you like:

```
git clone git@github.com:zepedropaixao/paixaocv.git
```

## Compile the .tex file

Make the modifications you wish and then compile the .tex file using XeLaTex

```
cd paixaocv
xelatex -synctex=1 -interaction=nonstopmode resume.tex
```

## Easy GUI for editing, previewing and compiling the .tex file 

I personally prefer to use Texmaker, to install it run in your terminal:

```
sudo apt-get install texlive-full
sudo apt-get install texmaker
```

