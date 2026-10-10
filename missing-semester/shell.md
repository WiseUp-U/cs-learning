# 1. grep
search file or directory containing the pattern given. Print the lines that match the pattern.
Might help me investigate files.

When exploring source files, you might come across a function. And you wonder where it is called, you could do
grep -n "function_name" source_file
That will print all the lines cotaining the function name along with the line number(-n).

Or you could do 'grep "your_name" thoughts.her' if you want to know you are in her thoughts at all.
Though it might fail to return correct information because if she remembers you as 'darling'.
In that case you could do 'grep -E "your_name|darling" thoughts.her'.

Those words inside double quotes are is called regular expression.
A regular expression is  a pattern that describes a set of strings.Like math expressions they are constructed by
using various operators to combine smaller expressions.
