🔐 Subhan's Secret Language (Python)

**This project implements a custom secret language in Python that can encode and decode words based on simple transformation rules.
It allows users to input words, encode them into a "secret" form, and then decode them back to the original text.**

📌 Features

**Custom Encoding Rules:**

**If the word length is less than 3:**

-Reverse the word.

**If the word length is 3 or more:**

-Move the first letter to the end.

-Add 3 random alphabets at the start and end of the word.

**Custom Decoding Rules:**

**If the word length is less than 3:**

-Reverse again to get the original.

**If the word length is 3 or more:**

-Remove the first and last 3 characters (random padding).

-Move the last letter to the start.

-Works with multiple words (input sentence).

⚡ **Example Run**
-Input
This is Subhan's secret language

**Output**
-Encoding:-  OeuhiTgd dsaSiab dXuvbhanaQ's NvtsceerV leanguageQiy
-Decoding:-  This is Subhan's secret language

🛠️ **How It Works**

-Word Processing

-The input string is split into words.

-Each word is encoded/decoded separately.

**Encoding Functions**
_____________________________________________________________________________________________
move_first_letter_to_end(word) → moves the first letter to the end.
_____________________________________________________________________________________________
add_random_alphabets(word, num_random=3) → adds 3 random letters before and after the word.
_____________________________________________________________________________________________
**Decoding Functions**
_____________________________________________________________________________________________
remove_first_and_last_three_chars(word) → removes 3 letters from start and end.
_____________________________________________________________________________________________
move_last_letter_to_start(word) → moves the last letter to the start.
_____________________________________________________________________________________________

📂 **File Structure**

secret_language.py → Main program file containing encoding/decoding logic.

▶️** How to Run**

-Clone or download this repository.

-Run the script in Python:

-python secret_language.py

-Enter any word/sentence when prompted.

📖 **Sample Cases**
Input  	Encoded Word	 Decoded Word
is	        si	            is
car	      XarcYZ           car

hello	AbchelloXyz	hello

✨ **Learning Outcomes**

-Working with string manipulation in Python.

-Using random and string libraries.

-Applying encoding/decoding logic.

-Implementing list comprehensions and joins for clean output.

👤 Author

Developed by Muhammad Subhan ✨
A fun Python project demonstrating creativity in text encoding & decoding.
