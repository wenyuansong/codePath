codePath
========

Help to quickly walk through source code logic 


Problem to solve:
  When you face tons of source code, what's the best way to quickly walk through source code and 
  get the best idea of code logic? With object oriented programming or lasy initialsing objects, it's hard to tell 
  which piece of code is actually executed in runtime. 
  What I often do is to add some logs to verify code logics. Well, it's stupid but helpful.
  So can we have a tool to parse source codes and add logs automatically so that once we run the program code logic 
  will be present to us instantly?  Sounds interesting? 
  
Solution on the plan:
  - Use antlr and existing C/Java grammer antlr files to provide source code parse functionality
  - Use log4j/log4c to provide logging functionality
  
  
  
