# calculator
BEC Test  date is May 22 2022

// calculator




 let operation =prompt('enter the operation such as +,-,*,/');
 const num1 = parseInt(prompt('enter the first number'));
 const num2 = parseInt(prompt('enter the second number'));
 let result ;

 if(operation == '+'){
   result = num1 + num2;
 }
 else if(operation == '-'){
  result = num1 - num2;
 }
 else if(operation == '*'){
  result = num1 * num2;
 }
 else{
  result = num1 / num2;
 }

 console.log(`${num1} ${operation} ${num2} = ${result}`);
