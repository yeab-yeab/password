import random      # helps you make choices
import string      # let's you do useful things with strings, like spliting them apart or changing the way they appear

adjectives = ['sleepy', 'slow', 'smelly',
    'wet', 'fat', 'red',
    'orange', 'yellow', 'green',
    'blue', 'purple', 'fluffy',
    'white', 'proud', 'brave']
# the list is in square brackets, Each item is a string, Put comma after each item

nouns = ['apple', 'dinosaur', 'ball',
    'toaster', 'goat', 'dragon',
    'hammer', 'duck', 'panda']

print("Welcome to password picker")


while True:
    for num in range(2):
        adjective = random.choice(adjectives)       # Holds a word choosen randomly from the adjectives list
        noun = random.choice(nouns)     # One of the nouns from the list is choosen and stored in this variable
        number = random.randrange(0, 100)       # To select a random number from 0 to 99
        special_char = random.choice(string.punctuation)        # To select a random punctuation character

        password = adjective + noun + str(number) + special_char
        print('Your new password is: %s' % password)

    response = input("Are you satisfied with the password? [y/n] : ")
    if response.lower() == 'y':
        print("Have a good day")
        break
    
        
