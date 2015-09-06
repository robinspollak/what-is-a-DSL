# Language
_What is the name of the language? Link the name to its webpage 
(if appropriate)._

[SQLAlchemy](http://www.sqlalchemy.org)

# Domain
_Describe the language's domain in five words._

SQL databases during python programming.

# Computational model
_What is the underlying computational model of this language? To answer this 
question, provide a high-level description (no more than 100 words) of the 
computation that occurs when someone executes a program in this language._

The SQLAlchemy code is translated into true SQL and executed as such. The model depends slightly on which SQL database being used but can translated into code to model, insert, select, join etc.


# DSL-ness
_Fowler writes about a spectrum of languages, from general-purpose languages to 
"purely" domain-specific. Where does the DSL you chose fall on this spectrum, 
and why?_ 

SQLAlchemy is closer almost purely domain specific. It can only be used for this one domain and is not turing complete.


# Internal or external?
_Is the language implemented as an internal or external DSL? 
Justify your answer._

SQLAlchemy is an internal DSL as it compiles as python, shares similar syntax, and can be among non-SQLAlchemy python code.


# Host language
_What language(s) was (were) used to implement the DSL?_

Python.


# Benefits
_Identify one potential benefit of the DSL: how is a programmer's life or a 
company's bottom line made easier by the existence of this language?_

This allows python programmers to treat SQL databases as collections of objects no matter how large the database grows. Also, allows to select from joins not just from tables.


# Drawbacks
_Identify one potential drawback of the DSL: what does a programmer or company 
lose by using this DSL instead of a general-purpose language?_

One drawback is that you are depending on an external library that is maintained by someone else so, as opposed to just writing the SQL yourself, you can't be sure everything works exactly as you would expect.
