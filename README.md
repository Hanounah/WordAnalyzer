Import the React, component from react and then import anything will be used inside code such styles, text, view and button from react native
I made class public using export default class which is extended component that import from react library
Set the initial state by using  constructor() for char =0 which is length of word, vowel letter=0 and consonants =0 and the reason it is assigned to 0 that we want to count when the user enter the word how many letter entered, vowel and consonant one.
I use arrow function called (WordAnalyzer) which is for looping through the word and examine the length of the word, count vowel letters and consonant also.
In the function, I redeclared the variable to be reached by the function(local) such redeclared vowel, consonants and char. The most important I call the word which user has entered using(this.state.word).
I assign the word.length to char variable for count the length of the word character and to displayed using this.state.char.
I loop through the word length to examine each character of the entered word and if it is vowel will count how many else will count the consonant letter
I used to Uppercase() for enabling user enter in any case such if enter lowercase will change it automatically to uppercase. Also, we can use tolowerCase() to do vice versa and by doing such these two operator it prevent us from doing many options in if statement.
I use (this.setstate) to change the state of all declared variable that is assigned to (0)
 using render() to display and render what is done by function and class.
In render() Using <TextInput onChangeText> to allow user enter the word and applying this.setstate for word to change its status that was assigned nothing ' '.
Lastly we displayed the char, volume and consonant letter by using this.state 
All the code is styled using Styles.js file(outsider) to style when displayed inside the render()
In styles.js we import stylesheet also from react native as we do in App.js to able declare stylesheet.
