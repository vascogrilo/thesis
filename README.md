### Title
**_Exploring an Extendable Live Environment for Scala_**

### Author
**Vasco André Costa Grilo**, FEUP, Student no. 100509125

### Supervisors
**Hugo Sereno Ferreira**, Assistant Professor at Department of Informatics Engineering, Faculty of Engineering of University of Porto.  
**Tiago Boldt Sousa**, Assistant Professor at Department of Informatics Engineering, Faculty of Engineering of University of Porto.  

### Workplace
Faculty of Engineering of University of Porto.  
Porto, Portugal.  

### Description

Among many tools available for coding with a programming language, one of the most used are the _Read-Eval-Print-Loops_. It is a great tool for discovering, exploring and getting to learn a new language. Its quickness and simplicity make it a great choice for experiencing the language over defining a program in a text file, run it through the compiler and execute it.  
Scala's _REPL_ is no exception to this. However, the results from interpreting instructions are verbosed and only consist in textual representation (usually the toString operation on the result).  
For some kind of statements or instructions this representation is just fine. For example, `val x = 1 + 1` would yield `x: Int = 2`, which is just fine. But what if we're dealing with `Lists` that represent a distribution of values that we want to see it as a bar chart? Or a function we want to see graphically with the evolution of the function over time. In a standard _REPL_ we can't achieve it.  
The goal is to explore and develop an extendable environment for Scala which will offer a wide set of graphical conversions on results from interpreting your instructions. Through the power of `implicits` in Scala we can easily define implicit conversions for all data types that can be applied before presenting a result.  
As well as exploring the advantages of `implicits` for graphical outputs we want to converge into a live development environment in which we don't have to explicitly tell the environment to compile our code but it will detect every entry point of instructions and automatically interpret the code and show results.  


### Aditional Pages and Drafts

  * https://github.com/vascogrilo/thesis/wiki/_pages
