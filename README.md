# linuxtopics
printing concept
variable conept
functions concept
conditions conepts
loops
exit status
I/P
O/P
final o/P
redirectors and 
SED editors
exaple


prinitng --The echo command in Linux is a built-in command that allows users to display lines of text or strings
eg echo [string]
   echo hello "madhan"
echo -e "hello \bgood  \bmorning"-----o/p "hellomadhankumar "
Options Available in `echo` command in Linux
1)\b : it removes all the spaces in between the text
2)\c : suppress trailing new line with backspace interpreter ‘-e‘ to continue without emitting new line
3)\n : this option creates a new line from where it is used.
4)\t : this option is used to create horizontal tab spaces.
5)\r : carriage return with backspace interpreter ‘-e‘ to have specified carriage return in output.
6)\v : this option is used to create vertical tab spaces.
7)\a : alert return with backspace interpreter ‘-e‘ to have sound alert.
8)-n: this option is used to omit echoing trailing newline.
9)echo *: this command will print all files/folders, similar to ls command.
10)Redirecting `echo` Output

colour concept ---basiclly linux by default has 6 colouring functions 
eg  echo -e "\e[31mThis text is red\e[0m"
\e[31m sets the text color to red.
\e[0m resets the text formatting to the default.
ANSI Code	Color
31        	Red
32	        Green
33	       Yellow
34	         Blue
35	         Magenta
36	          Cyan

Variables concpet ----A shell variable is a character string in a shell that stores some value. It could be an integer, filename, string, or some shell command itself. Basically, it is a pointer to the actual data stored in memory.
A variable name could contain any alphabet (a-z, A-Z), any digits (0-9), and an underscore ( _ ). However, a variable name must start with an alphabet or underscore. It can never start with a number.
eg variable_name = <variable data>
Variable Types
We can discuss three main types of variables:

1) Local Variable:
   Variables which are specific to the current instance of shell. They are basically used within the shell, but not available for the program or other shells that are started from within the current shell.

2) Environment Variable:
   These variables are commonly used to configure the behavior script and programs that are run by shell. Environment variables are only created once, after which they can be used by any user.

3) Shell Variables:
   Variables that are set by shell itself and help shell to work with functions correctly. It contains both,,, which means it has both, some variables are Environment variable, and some are Local Variables.