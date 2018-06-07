# -SESSION-4-ASSIGNMENT-2

1. x <- c(‘data.science.in.R’, ‘machine.learning.in.R’)
Perform the below string Operation:
• Replace the period character "." within each string with another character i.e. "-" minus sign.
> gsub(".", "-", x,fixed=TRUE)
[1] "data-science-in-R"     "machine-learning-in-R"

2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
• Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the object.


> d1 <-paste0("-", x)
> d1
[1] "-data.science.in.R"     "-machine.learning.in.R"
> d2<- paste("-data.science.in.R","-machine.learning.in.R")
> d2
[1] "-data.science.in.R -machine.learning.in.R"
