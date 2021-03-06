Chrisper: Check the style of your papers
========================================

Chrisper is a small utility that checks for common mistakes in the latex source of Computer Science papers.

The reference that we follow is [Bugs in Writing](http://www.amazon.com/BUGS-Writing-Revised-Guide-Debugging/dp/020137921X).


Install
-------

The only dependencies are "detex", which you can install
on a Debian derivative system with:

    sudo apt-get install texlive-extra-utils

and "nltk", which you can install with:

    sudo pip install nltk

If you want to be fancy and have the (optional) colored output,

     sudo pip install clint

Add chrisper in you path to use it, or copy it directly in
the root path of you awesome paper.

Usage
-----
 
    chrisper *.tex

Example
-------
An run of Chrisper on [this_tex_file](example_with_errors.tex) gives this output:

![Alt text](example_with_errors.png)

Contributing
------------

You're more than welcome :)

Related Work
-----------
* [some shell scripts](http://matt.might.net/articles/shell-scripts-for-passive-voice-weasel-words-duplicates/)
* [WDS](https://github.com/utapyngo/WritingSmellDetector)
* [stile-check.rb](http://www.cs.umd.edu/~nspring/software/style-check-readme.html)
