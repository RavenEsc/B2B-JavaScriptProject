# B2B Javascript Project

## Description
  This is my javascript code for the Barriers to Entry Application Process. Here I demonstrate a fully educated capstone project in Javascript.

## Criteria

Starting with the HTML wrapper code in the Code Editor...

- [ x ] You may or may not use a `<form>`. Note that there is no backend process or program to submit a form to. If you use a form and submit, you must suppress the default action or the page will clear/load unpredictable results.

- [ x ] Ask the user to input their first name, last name, a UserID, and a birthdate in type date format.  The UserID must contain an uppercase, a lowercase, a number, and be 8 to 12 chars long.  

- [ x ] Create a JS function to verify formats of the UserID field.

- [ x ] You will either need to use a For loop to iterate through your data fields character by character with JS functions like char.toUpperCase() and parsInt(char), or use Regular Expressions, to validate the UserID format.

- [ ] Use the following variables (with exact variable names) to hold the data:

  - uid is UserID.

  - fname is first name.

  - lname is last name.

  - birthday is birthday, using type 'date'.

- [ ] You have to write a function called “dateDiff” that accepts one date parameter and returns the number of days between the birthday provided and the current date.

- [ ] Create an “Accept” button to execute your functions and create the following output:

- [ ] If the UserID does not pass your verification, then print “Invalid UserID” to the Display window.

- [ ] If the fname, lname, or birthday fields are left empty then print “Invalid fname” etc…

- [ ] Print “fname lname you have been breathing for ### days!” where ### is the number returned by your dateDiff() function.  Remember to convert milliseconds to days and only return the integer (whole) number of days.

- [ ] If the number of days is less than (365*18) then print “You are probably not old enough to take this class!”

- [ ] Use document.getElementById().innerHtml to display results and information messages on the Display window.

- [ x ] Create a "For loop” that loops 20 times and uses code similar to:

- [ x ] let str = "";
str = str.padStart(i,”x”); // i is the loop counter

- [ x ] to print 20 lines of Xs from 1 to 20 Xs.  The first line should have a single X and the 20th line should have 20 Xs.

- [ x ] Your Xs should be printed on the Display page as depicted in the example below.

- [ ] Your code output should show in the Display window.  This serves as the equivalent of the browser window and shows the render of the DOM document you are coding.

## Acknowledgements
  Thank you to the challenge creators, this has been a fun and engaging challenge.
