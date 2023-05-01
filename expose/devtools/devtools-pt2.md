1. The bug is that it is concatenating the inputs num1 and num2 rather than adding them. 
2. I'd make sure that num1 and num2 are both treated as the appropriate data type like integers before adding them,
that way math is done to sum them instead of concatenate them. 

an example would be like for the line
let result = parseInt(num1) + parseInt(num2) ; 
