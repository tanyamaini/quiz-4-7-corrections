# Quiz 4-7 Corrections

## Quiz 4

### 11a.
```
function payingTheBill(){
  let p = document.getElementById("pay-the-bill");
  let restaurantName= prompt("What is your favorite restaurant?");
  let numberOfGuests= Number(prompt("How many guests would you like to invite to the restaurant?"));
  let totalBill= Number(prompt("What was the total cost of the dinner?"));
  let pricePerPerson = totalBill / (numberOfGuests + 1);
  p.innerHTML = `Dinner at ${restaurantName} doesn't come cheap! Everyone owes $${pricePerPerson}!`;
}
```

### 11b.
```
function classScheduling(){
  let numberOfStudents= Number(prompt("Enter the number of students in the class."));
  let courseName= prompt("Enter the name of a course being taught at your school.");
  let maxCapacity= Number(prompt("Enter the maximum capacity of a single section of the course."));
  let numberOfSections= numberOfStudents / maxCapacity;
  console.log(`${numberOfSections}sections of ${courseName} are required to satisfy the demand of ${numberOfStudents} students.`);
}
```


## Quiz 5

### 1.
An equals sign is not a valid relational operator in Javascript. It is a equality operator, as it sets two variables equal to each other. >=, !==, ===, <, >, !=, <=, and == are all relational operators.

### 3.
The two expressions that satisfy the missing condition are x===y and x!==y. This is because the code simply needs to check if x is or is not equal to y. No conversions are necessary. Therefore, three equal signs are used, for checking if the two variabels are equal. One exclamation point and two equal signs are used when checking that they are not equal however, as the expclamation point can be considered to count as an equal sign. It is not possible to have an exclamation point and then three equal signs. Thus, the two expressions that satisfy the missing condition are x===y and x!==y.

### 5.
A question mark (?) is not a logical operator. It is a ternary operator. Logical operators are used to test if an expression is for true or false. These include !, ||, and &&.

### 6.
The simplest way to convert a student's numeric quiz score to an approximate letter grade is to use the if and if else statements. The switch statement is lengthy, and using several ifs with only one conditional statement will cause the score to fit in the category it really belongs in plus the ones below. The if statements with two conditional statements are also simply lengthy, therefore the ifs and if elses are most effective.

### 11.
The for loop with "let i = 0; i < 5; i++" inside the parathesis represents a valid for loop that will execute at least once and then terminate. This is because the value of i must be set, so the word "let" should be used as it is not previously defined. Also, i must always be less than 5, or else the loop would continue forever as it keeps adding one to i. The i++ is the code that adds 1 to i each time the code loops. If this wasn't there, the code would not loop to each value of i. 


## Quiz 6

## 1.
The built-in functions "Math.random" and "prompt" are designed to return a value. They will return a value when they complete their jobs in the code.

### 3.
The built-in functions "prompt", "alert", and "console.log" accept parameters. It is possible to customize what goes inside the parenthesis, and the functions can accept different parameters. Functions such as "Math.random" however cannot. "Math.random" can only return a value.


## Quiz 7

### 4.
The pieces of code "cars.includes(car)", "cars.indexOf(car) !== -1", and "cars.lastIndexOf(car) !== -1" are possible replacements for the missing code. They all check to see if the value of "car" is part of the array "cars".

### 6.
Setting specific values for different indexes, pushing multiple values at once, and pushing one value at one time will add the values to an array. An example of setting an index of an array to a value is: "numbers[3] = 8;". An example of pushing mutliple values at once is: "numbers.push(8, 10, 12);". An example of pushing one value at a time is: "numbers.push(8);". All three of these will add the specified variable into the array "numbers".
