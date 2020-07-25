
Instructions to check out and compile the paper:

project TDR
cvs co -l TDR
cvs co TDR/general
cvs co TDR/notes/CFT-09-016
cd TDR/notes/CFT-09-016

"Compile" the LaTex using 
for bash:
eval `../../tdr runtime -sh`

for csh or tcsh:
eval `../../tdr runtime -csh`

and then:

tdr --style=in build CFT-09-016.tex
