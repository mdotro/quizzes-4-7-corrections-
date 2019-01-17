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

04. 

