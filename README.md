# recursion-checkpoint

# Define a function named IsPalindrome that takes a word as input and returns a Boolean value indicating whether the word is a palindrome.

# Inside the IsPalindrome function, initialize two counters, left and right, to keep track of the characters at the ends of the word. Set left to 1 (indicating the leftmost character) and right to the length of the word (indicating the rightmost character).

# Start a loop that continues as long as left is less than right.

# Inside the loop, compare the characters at the left and right positions of the word.

# If the characters are not equal, immediately return False from the function, indicating that the word is not a palindrome.

# If the characters are equal, increment left by 1 and decrement right by 1 to move towards the center of the word.

# After the loop ends, return True from the function, indicating that the word is a palindrome.

# If the loop is never entered, it means the word is empty or contains a single character, which are considered palindromes. In this case, you can add a check at the beginning of the function to return True for an empty word or a word with a length of 1.
