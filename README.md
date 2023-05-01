Download Link: https://assignmentchef.com/product/solved-ccucd-project-2-parser
<br>
<strong> </strong>The goal of our project this semester is to develop a prototype C compiler. This is done by compiling C programs into processors such as x86, MIPS, ARM, or pseudo assemblies. In this class we will use Java assembly code (Jasmin, http://jasmin.sourceforge.net/) as the target codes. <strong>The project is divided into several parts including language definition, lexical analyzer, C-grammar, symbol table handlings, parser, and code generation.</strong> In the project 2, you will need to decide the set of language features you want to support in your compiler, and write the <strong>syntax analyzer</strong>.




Instead of generating codes, you will only need to output grammar rules in the code generator part to test whether the grammar is correctly passed. An example code may look like:

program: VOID ID ‘(‘ ‘)’ ‘{‘ declarations stmts ‘}’

{ if (TRACEON)

System.out.println(“program: VOID ID ( ) { declarations stmts }”);}

declarations: type ID ‘;’ declarations

{ if (TRACEON)

System.out.println(“declarations: type ID ; declarations”); } …




You can find a demo C grammar in this link:

<a href="http://www.antlr.org/download/examples-v3.tar.gz">http://www.antlr.org/download/examples</a><a href="http://www.antlr.org/download/examples-v3.tar.gz">–</a><a href="http://www.antlr.org/download/examples-v3.tar.gz">v3.tar.gz</a><a href="http://www.antlr.org/download/examples-v3.tar.gz">.</a>







In your hand-in report, you need to have the followings:

<ul>

 <li><strong>To define the subset of the language which you want to choose from C. </strong></li>

 <li>Give a set of testing programs that can illustrate the features of your subset of the language. (at least 3 test programs)</li>

 <li>Use the “<strong>ANTLR</strong>” to help you develop the parser.</li>

 <li>You can use <strong>Java</strong> or <strong>other languages</strong> to write your parser. (<strong>Java is recommended</strong>)</li>

 <li>Please ensure your program can be executed under the <strong>mcore8</strong> or <strong>cs.ccu.edu.tw</strong> workstation.</li>

</ul>


