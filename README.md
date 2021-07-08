# Simple_Password_Generator
Generates a password.

In this code;

import random imports the random module, which contains a variety of things to do with random number generation.

The randint() function can be used to simulate a lucky draw situation. It returns an integer number selected element from the specified range.

For a password to be strong enough the capital letters, small letters and symbols are to be used.

*chc = s.ascii_letters+s.digits+s.punctuation*                     

Choice takes the ascii letters, digits and the punctuations 

__*password= "".join(choice(chc) for x in range (randint(5,16)))*__

Then joins the choice in the given range, and the password is generated.
