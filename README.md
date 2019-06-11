# USAesthetics

write me a function that parses the Preamble to the US Constitution (you can hard-code it as a string) and returns a count of how many words begin with 't', how many end with 'e', and how many begin with 't' and end with 'e'. JavaScript or Dart would be the preferred languages to accomplish this. I'll leave it to you to determine the best way to submit your work (on a webpage, as a link to a github repo, etc). I need to be able to execute what you send me, and see your code generate its answer(s).  And what would be extremely helpful is if you document your process and any problems you ran into along the way, and describe how you solved them.

// ok im gonna code this in java script
// first step is putting the preamble into an array and making it a variable
//im think a for loop with conditions
///well ill need to create a quick line to split the array into single letters
// if a t follows a space, add to the tally of "starts with T" (kind of cheap since I happen to know the first letter does not follow a space but also happens to not be a "T" if it was i would have to just add one to this equation)
//if a "e" preceeds a space, add to the tally of "ends with E"
// the final conditional will be if ... and ... then add to this tally, probably the most tinkering to do

actually maybe ill set it up in it's own repo and let the user click simple buttons to tally starts with... ends with... it will have to re-parse the array but it might be the best option for aesthetics. 

/// for furutre dev i could parse the whole array with all the conditionals regardless of which button was clicked then store those values and then display the value with the correclated button, not sure if that would make it more efficicent but i feel like it would save running the for loop every time
unless the page was refereshed
