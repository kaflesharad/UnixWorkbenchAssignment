# UnixWorkbenchAssignment
Guessing Game Assignment

all : README.md

README.md : guessinggame.sh
  echo "#Coursera : The Unix Workbench" > README.md
  echo "##Peer Graded Assignment ">> README.md
  echo "README.md created">> README.md
  echo "* Lines of code in guessinggame.sh: $$(wc -l guessinggame.sh  | egrep -o "[0-9]+")" >> README.md
