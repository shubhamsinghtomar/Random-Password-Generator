# Random-Password-Generator
We import the random module to generate random characters and the string module to access predefined string constants.
The generate_password function takes a single parameter length, which represents the desired length of the password.
The characters variable is defined as the concatenation of string.ascii_letters (containing all ASCII letters), string.digits (containing all digits), and string.punctuation (containing all punctuation marks).
We then use a list comprehension along with the random.choice function to randomly select characters from the characters string length number of times. These characters are joined together using the str.join method to form the final password.
The generated password is returned by the generate_password function.
Finally, we specify the desired password_length, call the generate_password function with this length, and print the generated password.
Please note that the string.punctuation constant includes a specific set of punctuation marks. If you want to customize the set of characters used in the password, you can modify the characters variable accordingly.

Code Implementation:
First, take the length of the password as input. Then we can display a prompt about the possible list of characters that a user wants to include in the password –

For including letters in the character set append string.ascii_letters in the character list.
For including letters in the character set append string.digits in the character list.
For including letters in character set append string.punctuation in the character list.
Run a for loop till the length of the password and in each iteration choose a random character using random.choice() from characterList. Finally, print the password
