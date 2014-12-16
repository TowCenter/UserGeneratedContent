.tex file manually created from .pdf

generate html w/pandoc:

pandoc UGC.tex -o UGC.html

Create CMS-ready files:
python CreateRightRail.py UGC.html


generate md w/pandoc:

pandoc UGC.tex -o UGC.md

Generate GitBook files:
python GenerateGitBook.py UGC.html

