Step by Step Instructions (Pseudo Code)

1) Call on the data for the checkboxes with document.querySelectorAll
  a Inspect the page and find out which elements you need to call on. In this case, you will need the inbox and the input[type="checkbox"] within the inbox class.

2) Loop over the checkboxes and add an event listener and call upon the function to fulfill argument of checking the boxes in between the 2 selected checkboxes.

3) Definte the function 

4) Make if statements within the function that check if the shift key is held down AND that the user is checking the boxes. 

5) Loop over every single checkbox within the if statement. Makes sure criteria is first met before function runs.

6) Make sure that the 1st click and second click are the parameters to start the inBetween process with an if statement.
  a) When the loop runs, you have to change the inBetween status of the parameters or else it will include them in the inBetween process. set the inBetween of the 2 parameters to the opposite to bypass this with a nested if statement. 

7) Once all requirements are met and inBetween is established make another if statement. 
  a) If inBetween, set the checkbox.checked status to true. 