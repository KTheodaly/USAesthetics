# USAesthetics

## The Goal

write a function that parses the Preamble to the US Constitution (you can hard-code it as a string) and returns a count of how many words begin with 't', how many end with 'e', and how many begin with 't' and end with 'e'. JavaScript or Dart would be the preferred languages to accomplish this. Need to be able to execute, and see your code generate its answer(s).

## Initial Plan

* javascript
* get the preamble into an array, make it a variable
* Could probably write a single for loop with multiple conditions, the letters
  ** maybe use .split() and look at what follows or preceeds a space?
  ** I'll need variables and increment their tally based on that
* Actually maybe Ill set it up in it's own repo and let the user click simple buttons see the tally: starts with... ends with... so on.       Three seperate functions each corresponding with a button. 
* Might have to reloop the array but it might be the best option for aesthetics. 

## The Results

* When the user open the page, they see the Preamble and the three conditions to display
* The buttons have click events that trigger their corresponding function, and within those functions is a line of code that appends the     updated tally to the correct div, only once the loop has run
* In the console you can see the log of the loop tallying up how many instances of each condition there are, if you click the button again,   the loop will calculate the tally again in the console but your tally will remain the same on the front end
* The display clears if the user refreshes the page
* Javascript, HTML, CSS, Bootstrap- I just added a little font styling and a background image, very minimal, and some nice little bootstrap   columns for the grid

## Challenges / Final Thoughts

* The hardest part for me was figuring out how to target the character at the end of a word. I thought I would be able to just .reverse() the string but I ended up having to tinker around with the second function until I figured out the last letter would be 
  string[i].length-1
* The last function was pretty fun because I already had everything I needed for it, but I've never had the occasion to use a double       ampersand since learning it towards the end of my course, so I was happy to see it working on the first go
* I had a little bit of confusion towards the end of construction because the 2nd, 3rd & so on button clicks were adding values to the tallies, which turned out to just be carelessness with variables, easy enough to sort out
* I do think there is probably a more efficient way to create this app, like having a single function that checks for all the conditions  and tallys them regardless of the button clicked, and then using the click events on particular buttons to display the correct value. For future dev I could probably change this without much effort to save running through the loop each time a button is clicked. However, the consitions on this app right now are pretty clean looking and they work, so I like that about them
