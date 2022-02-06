# Code-Style
\documentclass{article}

\usepackage[utf8]{inputenc}
\usepackage{authblk}
\usepackage[dvipsnames]{xcolor}
\usepackage{amsmath}

\title{Code Style}
\author{Elizaweta Chernova ; IA-031 ;}
\affil{SibSUTIS, email: elizaweta\_02@mail.ru .}
\date{January 2022}

\begin{document}

\maketitle

\section{Introduction}
The code style guide is used in order to provide a unified rules how to write a code for a specific project. It is much easier to read/write/edit the code when the project has a consistent style.
\section{C++\cite{CPP}}.
\section{Code-Style for C++\cite{CPP1} \cite{CPP2}} 
\begin{tabular}{ |p {350}| }
\hline \\
\textbf{\Large {Gaps}}\\ \\ 

\textbf{Gaps} are placed between operators and operands \\
For example: \\
int x = ((5 + 3) / 2) + sqrt(1024) ; \\ \\
\hline \\ 

\textbf{\Large {Braces}}\\ \\
The \textbf{closing brace} is placed on a new line at the level of the part of the code it delimits \\ 
For example: \\
void function(arguments)\{ \\ \\ 
\ \	\ \ \ ...\\
\} \\ \\
Leave a blank line between \textbf{functions and expression groups}\\
For example: \\
void function\_1(arguments)\{ \\ 
\ \	\ \ \ ...\\
\} \\  \\ 
void function\_2(arguments)\{ \\ \\ 
\ \	\ \ \...\\
\} \\ \\
\hline \\
\textbf{\Large {Names and variables}}\\ \\
\textbf{Variables and functions} are called descriptive names in a specific format\\
The \textbf{function} name begins with an uppercase letter and each word in the name capitalized\\
For example: \\
int FirstName;\\
void function\_1();\\ \\
\textbf{Each variable} is declared on a new line\\
For example: \\
int a;\\ 
float b;\\ \\
\hline 
\end{tabular} \\ \\
\begin{tabular}{ |p {350}| }
\hline \\
\textbf{Variables} can be enumerated in a string if they are of the same type\\
For example: \\
int a, b, c;\\\\ 
\textbf{Classes} are called descriptive names\\
class MyClass\{\\
\ \ \ \ \ \ ... \\
\} \\ \\
\hline \\
\textbf{\Large {For, while, if, else}}\\ \\
\textbf{Braces} are always used in for, while, if, else.\\
Examples:\\
for\ (int i = 0;\ i\leq size;\ i++ )\{ \\
\ \ \ \ \ ... ;\\
\} \\ \\
while\ (k\ \leq\ 10) 
\{
\ \ \ \ ...\ ;\\
\} \\ \\ 
int main()
\{\\
\ \ \ \ k=25\ ;\\
\ \ \ \ if (k != 0) \\
\ \ \ \ \{\\
\ \ \ \ \ \ \ \ k = k - 5;\\
\ \ \ \ \}\\
\ \ \ \ else\\
\ \ \ \ \{\\
\ \ \ \ \ \ \ \ k = k + 6 ;\\
\ \ \ \ \}\\
\ \ \ \ ... \\
\} \\ \\




\\ \hline \\

\textbf{\Large {Output on display}}\\ \\
\textbf{Screen output} with the cout statement \\ \\
For example:\\
cout \ll "a =" \ll a \ll endl ;\\ \\
\hline 
\end{tabular}\\ \\ \\ 

\begin{tabular}{|p{350}|}
\hline \\ 
\textbf{\Large {Assigning a text value to a string}}\\ \\
Text is written to a variable of type string
For example:\\
string str = "Hello world";\\ \\
\hline\\
\textbf{\Large {Comments to sections of code}}\\ \\
\textbf{Comments to sections of code} are written through // , in cases of an ambiguous function name when working in a team for understanding the code by all programmers\\
For example:\\
int a; //variable to store the number of passes through the loop\\
\hline
\end{tabular}\\
\newpage
\section{Conclusion}
\LARGE{I mastered the Latex commands and learned how to work with them, I also made Code style , which will help to design the program code beautifully and correctly}\\
\hline
\begin{thebibliography}{4}
\bibitem{CPP}
ISO/IEC 14882 Programming languages — C++.
\bibitem{CPP1}
https://docs.opentitan.org/doc/rm/c\_cpp\_coding\_style/
\bibitem{CPP2}
https://google.github.io/styleguide/cppguide.html
\bibitem{CPP3}
http://www.ccas.ru/voron/download/books/tex/klimenko96sprav.pdf

\end{thebibliography}

\end{document}