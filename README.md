# quizzes-4-7-corrections

This is the repository where I will be correcting the problems for quizzes 4-7

## Quiz 4

06. For this problem I was asked to provide the correct ways to correctly display the outcome of pressing a button. I was given multiple choices all of which could've been correct. I selected one that was correct, but didnt realize tht you could've simplified the code even more and put everything into one line. I should've selected the answer, "function sayHi() {document.getElementById("my-paragraph").innerHTML = "Hi, there!";}" as well as the other one I selected. 

09. For this problem I was asked to  show all the correct ways to create a variable holding the value of 9. I chose "let x; x = 27;" as well as "let x = 27;" I was fooled here because since it was a pick more than one type of question I felt it was necessary to choose more than one answer. "let x; x = 27;" means that you are establishing x as a variable but then setting it equal to 27. "let x = 27;" was the only correct answer out of the four and I did select this but I also lost points for choosing the other along with it. 
 
11a.  function yourName() {
  let name = prompt("Please enter your name.");
  let age = prompt("Please enter your age. ");
  let nextYear = (age + 1);
  let p = document.getElementById('asked-and-answered');
  p.innerhtml = ("Hello " name "." "When do you turn " nextYear "?");
}
For this code block, I noticed that i forgot to add "+" in between ("Hello " name "." "When do you turn " nextYear "?"); This strip of code should actually look like this "p.innerhtml = ("Hello " + name + "." + "When do you turn " + nextYear + "?");" Also, I should have added "Number" in front of "let nextYear = Number(age + 1);" so that the computer knows to use only numbers, and not any other values.  So the final product should look like this: 
function yourName() {
  let name = prompt("Please enter your name.");
  let age = prompt("Please enter your age. ");
  let nextYear = Number(age + 1);
  let p = document.getElementById('asked-and-answered');
  p.innerhtml = ("Hello " + name + "." + "When do you turn " + nextYear + "?");
}

11b. function classTrip() {
  let numberOfstudents = prompt("Please enter the number of students attending the trip.");
  let numberOfchaps = prompt("Please enter the number of chaperones, including the teachers, attending the trip.");
  let capacityOfbusses = prompt("Please enter the maximum amount of space on each bus.");
  let numberOfbusses = ((numberOfstudents + numberOfchaps) / capacityOfbusses);
  let p = document.getElementById('field-trip-equation');
  console.log(numberOfbusses "busses are required to accommodate " numberOfstudents " students and " numberOfchaps " chaperones.");
}
For this block of code I made the same mistakes as I did in 11a. I should have added "+" in "console.log(numberOfbusses "busses are required to accommodate " numberOfstudents " students and " numberOfchaps " chaperones.");" This strip of code should actually look like this: :"console.log(numberOfbusses + "busses are required to accommodate " + numberOfstudents " + students and " + numberOfchaps " + chaperones.");" Also I should've added "Number," in front of "let numberOfbusses = (Number(numberOfstudents + numberOfchaps) / capacityOfbusses);" so that the computer knows to use only numbers, and not any other values. in front of  So the final product should look like this: 
function classTrip() {
  let numberOfstudents = prompt("Please enter the number of students attending the trip.");
  let numberOfchaps = prompt("Please enter the number of chaperones, including the teachers, attending the trip.");
  let capacityOfbusses = prompt("Please enter the maximum amount of space on each bus.");
  let numberOfbusses = (Number(numberOfstudents + numberOfchaps) / capacityOfbusses);
  let p = document.getElementById('field-trip-equation');
  console.log(numberOfbusses + "busses are required to accommodate " + numberOfstudents " + students and " + numberOfchaps + " chaperones.");
}

## Quiz 5

01. For this question I was asked to show what would be logged to the console for the code block,
"let a = "hello";
console.log(!a);
console.log(!!a);"
I didn't realize that "!" and "!!" both mean false and I put my answer as "true then false." I should've put "false, then false," because "!" and "!!" both mean false. 

02. For this question I was asked to select all the relational operators for Javascript. I confused these with the logical operators and mixed them all up. I should've chosen "!==", "!=", ">", "<", "<=", ">=", "==" and "===" as opposed to "&&", "||", and "!". 
"!==", "!=", ">", "<", "<=", ">=", "==" and "===" are all relational operators. 

03. For this question I was asked to select all the logical operators out of the given answers. For this I mixed up the logical operators and the relational operators. I should have selected "&&", "||", and "!", as opposed to "!==", "!=", ">", "<", "<=", ">=", "==" and "===". "&&", "||", and "!" are logical operators. 

04. If a is greater then both b and c I would know that a is the biggest of the three variables, but I thought since c < a and c > b then c would be the middle variable so I thought an "&&" was the correct operator to use here. But an "||" operator would work best here because you would know that c is the middle variable if it was smaller then a or bigger than b.

05. The correct answer her was x === y and x !== y. This is the correct answer because this would tell me that both the types of the values such as number and string are equal, and it would also tell me that the values are equal. !== this tells me that the value types are different or the values are differnt meaning they are not equal. 

06. switch (dayCode)
   case 0: day = "Monday"; break;
   case 1: day = "Tuesday"; break;
   case 2: day = "Wednesday"; break;
   case 3: day = "Thursday"; break;
   case 4: day = "Friday"; break;
   case 5: day = "Saturday"; break;
   case 6: day = "Sunday"; break;
   default: day = "an unknown day"; break;
}
Is the correct answer for this problem. I did this problem wrong because i thought quotation marks should be around 0,1,2,3,4,5,6, and default, but it turns out there shouldn't be. There should only be quotation marks around Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, and an unkown day.

07. if (a < b)
{
    // do something
}

if (a < b) {
    // do something
} 
Were the correct answers for this problem. The reason I got this problem wrong was because I thought a semicolon was need after each of the paraentheses but they were not needed. 

08. if (score >= 90) {
    letterGrade = "A";
} else if (score >= 80) {
    letterGrade = "B";
} else if (score >= 70) {
    letterGrade = "C";
} else if (score >= 60) {
    letterGrade = "D";
} else {
    letterGrade = "F";
} 
Was the correct answer for thsi problem. What I did wrong here was I didn't realize that you could use a bunch of else if functions to do this equation. I thought that you could just make a function and write out it all out in a bunch of seperate lines of code, but this would just run all at once as opposed into a checking order.

09. Going into this quiz I wasn't sure how to use a else if statement evidently, and for this problem the correct way to do this was to add a else if statement. I thought you could've created a nested if statement and that would work, but the best and correct way of doing this was creating an else if statement. 

12. In this problem I thought that the problem being described could be satisfied by a do while statement. But, the correct way of going about completing this problem was through two different do statements that used "++" and "--". I also thought only "--" was needed to solve. 

13. For this problem I was asked to state the primary difference between a while and do while function. Originally I thought it was A while loop is designed to iterate an undetermined number of times, whereas a do...while loop is designed to iterate a set and specific number of times. But, it turned out it was A while loop check its condition before running the loop body, whereas a do...while loop checks its condition after running the loop body.

14. For this problem I was asked to tell if the statement "Anything written in the form a while (or do...while) loop can be achieved with an equivalent for loop and vice-a-versa," was true or false. I said that it was false, but it turns out that this statement was true. "Anything written in the form a while (or do...while) loop can be achieved with an equivalent for loop and vice-a-versa," is true. 

## Quiz 6

02. For this problem I was asked to show the correct code snipet for a return function. I didn't relaize that you didn't need to use the prompts in the original code snipet for the return function so I used the code snipet with the prompts from the original code snipet. the correct answer was:
function divide(a, b) {
    return a / b;
}

03. For this problem I was asked different ways to multiply the 3 variables in the parameter for the function. I picked two of the three corect answers, but I didn't pick the third because it look as if a issue would occur due to all the undefined values. It turns out this code snipet would solve the problem correctly. The answer I forgot to select was: 
function multiply(a, b, c, d) {
    if (a !=== undefined && b !== undefined && c !== undefined && d !== undefined) {
        return a * b * c * d;
    else if (a !=== undefined && b !== undefined && c !== undefined) {
        return a * b * c;
    } else if (a !=== undefined && b !== undefined) {
        return a * b;
    } else if (a !=== undefined) {
        return a;
    }
}

06. For this problem I was asked to show what would be printed to the console after executing the code snipet given. i didn't know that undefined would be printed to console if there was no value for a variable and thought that it would just come out as blank if there was no value and selected: "I need to do chores, homework, and... So busy!"

08. For this problem I was asked to show all the correct ways to console.log() the function subtract. I picked to of the correct ways to do this task, but I forgot to select the option console.log(subtract); which was the simplest of the ways most likely. Since subtract was in the parameter, the solution of the function would be automatically logged.

09. For this problem i was asked what would be logged if a variable had no value in a parameter. i thought that when a variable is logged and has no value, nothing would show, but the word undefined actually shows,which was the correct answer to this problem. 

10. For this problem i was asked to show the functions that would return a value after input. I knew prompt would, but I forgot that Math.random would also return a fucntion. This was one of the most simple questions that I screwed up. 

12. For this problem I was asked to show what would be logged to console after the code snipet was executed. In the code snipet there was console.log(d) but there was no d variable in the parameters for the function. But, embedded in the function was var d = 4, but I still  didn't think this would make a difference and undefined or four would be logged. Turned out 4 would only be logged. 

## Quiz 7

02. For this problem I was asked to show the different ways of filling in the missing part of the code snipet given. I selected one correct answer, but then I selected an incorrect one and forgot to select the other correct answer. I thought to console log an array you need console.log(list[item]) but you could just console.log(item).

05. For this problem I was asked to select all the correct ways of adding three more values to an array. I selected two of three, but I didn;t think you coud just assign values to variables that didn't exeist in an array. Apparently you can and this was one of the correct asnwers. 

06. For this problem I was asked to find the missing part of the given code snipet. I answered two of the three correct, but I chose one wrong answer and forgot to choose one of the right answers. The answer "cars.indexOf(car) !== -1," was correct and this said that it didn't equal the vaule held at -1. I didn't think this was a valid answer, but it was and I should've chose it. 

