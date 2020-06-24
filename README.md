1- Import the React, component from react and then import anything will be used inside code such styles, text, view and button from react native

2- I made class public using export default class which is extended component that import from react .

3- Set the initial state by using  constructor() for char =0 which is length of word, vowel letter=0 and consonants =0 and the reason it is assigned to 0 that we want to count when the user enter the word how many letter entered, vowel and consonant also.

4-I use arrow function called (WordAnalyzer) which is for looping through the word and examine the length of the word, count vowel letters and consonant also.

5- In the function, I redeclared the variable to be reached by the function(local) such redeclared vowel, consonants and char. Also, declared the word by using this.state.word to set its initial declaration then updated according to what user will enter.

6- I have used string.split to make array of character called (input) then assign the its length to variable named (char) to count the length of the word entered and assign it  to char.

7- I loop through the word length to examine each character of the entered word then if it is vowel character will count how many else will count the consonant letter.

8- I used to Uppercase() for enabling user enter in any case such if enter lowercase will change it automatically to uppercase. Also, we can use tolowerCase() to do vice versa and by doing such these two operator, it will make it easier for us by doing not many options in if statement.

9- I use (this.setstate) to change the state of all declared variable that is assigned to (0)
 using render() to display and render what is done by function and class.
 
10- In render() Using <TextInput onChangeText> to allow user enter the word and applying this.setstate for word to change its status that was assigned nothing ' '.
       
11-Lastly we displayed the char, volume and consonant letter by using this.state 

12-All the code is styled using Styles.js file(outsider) to style when displayed inside the render()

13- In styles.js we import stylesheet also from react native as we do in App.js to be able using stylesheet.
