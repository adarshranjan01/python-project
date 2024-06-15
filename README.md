randint(1, 100) 
# generate random number guess = -1
# initialize guess to an invalid value while guess != number: guess_str = input("Enter your guess: ")
guess = int(guess_str) 
if guess < number: print("Too low, try again. ") 
elif guess > number: print("Too high, try again. ") 
print(f"Congratulations!

--------------------------------------------------------------------------------------------------------------------------------------------------

To keep track of all your guesses, you'll use a list. 
You can initialize the list with five underscores as placeholders for future guesses. 
Then, as the user makes a guess, you'll overwrite the placeholder.
