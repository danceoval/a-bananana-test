# Banana Append

Bananas make everything better! In this assignment you will write a
function that adds the word Bananas to the end of any text.

Write a function named `add_bananas` that:
- Takes one parameter, a string.
- Appends exactly ` Bananas!` to the end of it. There is one space before the capital B, and the text ends with an exclamation mark.
- Returns the new string. The function should return the string, not print it.

Then write the main part of your program. It should:
- Read one line of text from the user using `input()`.
- Call `add_bananas` with that text.
- Print the returned string on its own line.

Example:
  Enter some text: I like
  I like Bananas!

Another example:
  Enter some text: Fruit salad with
  Fruit salad with Bananas!

Note: The tests look at the end of your program's output, so you can word your
"Enter some text" prompt however you like. Just make sure the last line printed
is the new string, with nothing added after it.

Edge cases to consider:
- The user types an empty line. The result is then ` Bananas!` (it starts with a space).
- The text already ends with a space. Do not remove it. Just append ` Bananas!`.
- The text already contains the word Bananas. Still append ` Bananas!`.
