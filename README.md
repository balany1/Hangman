# Hangmanattempt2
~ This project works in the following order
#Initialise 5 attributes

# The play_game method calls the ask_letter method

# The ask_letter method asks for an input and checks to see the length of the input
# If the length of the input is 1 then the code checks to see if the letter has already been tried, if not then the input is required again
# If the letter has not already been tried then the letter tried is appended to the empty list of attempted letters
# If the input meets these checks then the codes calls the check_letter method

# check_letter first converts any input to lower case
# if the letter is in the word, then the first for loop checks each index of the word in question and replaces the dashes with the letter guessed

# if the letter is not in the word, then the number of lives is reduced, the user is informed of how many lives they have left 

# after this the code then reverts to the play_game method and checks to see if there are any dashes left or the num of lives is zero which will produce the "You have won" or "You have lost" respectively


