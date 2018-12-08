# Scanner-parser
Group work from my Programming Languages class (with Kyle Beard and Troy Tully).
Description is in CMPT 341 — Homework 4.pdf.


To run:

jFlex/bin/jflex algebra.jflex

java -jar java-cup-11b.jar algebra.jcup

javac -cp .:java-cup-11b-runtime.jar *.java

java -cp .:java-cup-11b-runtime.jar AlegbraParserTest


Modify input.txt to test different statements.


For this assignment we had to create a scanner-parser for a simple made up language using JFlex and Java Cup.
The hardest part was figuring out the grammar for the parser (jcup file), especially how the print and input functions had to fit in the picture. Debugging it was also tricky because of the interaction between the scanner and the parser. We weren't able to work on the extra credit questions because we ran out of time fixing some bugs.
Working on this project in a group wasn't easy because after the initial brainstorming session where we worked together to decide on the tokens and discussed ideas for the grammar, there wasn't a good way to split the work between us because of how closely dependent each part is to the others, so there was ultimately one person writing the code, even if the other two could make suggestions. I fell like we were able to work well together anyway, and everyone made valuable contributions.
