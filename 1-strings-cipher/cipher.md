### if not char.isalpha()

The line if not char.isalpha(): is used to check if the current character (char) in the message is not an alphabetic character.

Here's a breakdown of what this line does:

char.isalpha(): This method returns True if the character is an alphabetic letter (i.e., a-z or A-Z) and False otherwise.
not char.isalpha(): This negates the result of char.isalpha(). So, it will be True if char is not an alphabetic letter (e.g., a space, punctuation, number, etc.), and False if char is an alphabetic letter.

In the context of the code, if char is not an alphabetic character (like a space or punctuation), the code appends char directly to final_message without any changes. This ensures that spaces, punctuation, and other non-alphabetic characters are preserved in their original form in the encrypted or decrypted message.

### .isalpha()

_The .isalpha() method is a built-in string method in Python that checks whether all the characters in a string are alphabetic (i.e., letters from A-Z or a-z). It returns True if all characters in the string are alphabetic and there is at least one character; otherwise, it returns False._
