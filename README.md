# Password-Generator
This Python program generates a strong and unique password based on user input. The password consists of a combination of letters, numbers, and symbols.

Features:
- User can specify the number of letters, numbers, and symbols in the password
- Password is generated randomly from a predefined set of characters
- Password is shuffled to ensure randomness

How it works:
1. The program welcomes the user and asks for the number of letters, numbers, and symbols desired in the password.
2. The user's input is stored in variables n_letters, n_numbers, and n_symbols.
3. The program creates an empty list password_list to store the password characters.
4. The program loops through the user's input and randomly selects characters from the letters, numbers, and symbols lists.
5. The selected characters are added to the password_list.
6. The password_list is shuffled using the random.shuffle function to ensure randomness.
7. The program concatenates the characters in password_list to form the final password.
8. The final password is printed to the console.
This code demonstrates basic Python concepts such as lists, loops, conditional statements, and random number generation.
