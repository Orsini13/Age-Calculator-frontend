let userInput = document.getElementById("date");
userInput.max = new Date().toISOString().split("T")[0];
//this above makes the calendar limit the user input in date to the current date 

 function  getDaysInMonth(year, month){
    return new Date(year, month, 0).getDate();
}
//this above will help get the exact nmber of date in that month... in consideration of the month of february that has 28/29 days

in this project, console.log was used cause the result of the variable wont be 100% efficient, so the complete result will be in the console
