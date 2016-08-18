#!/usr/bin/python

##Initilize the dictionary to store the answers from the user
answers = {}

##Get the input for the pluralNoun
answerInput = input("Enter the answer for the pluralNoun blank space:");
answers['pluralNoun'] = answerInput

##Get the input for the pluralNoun2
answerInput = input("Enter the answer for the pluralNoun2 blank space:");
answers['pluralNoun2'] = answerInput

##Get the input for the adjective
answerInput = input("Enter the answer for the adjective blank space:");
answers['adjective'] = answerInput

##Get the input for the noun
answerInput = input("Enter the answer for the noun blank space:");
answers['noun'] = answerInput

##Get the input for the noun2
answerInput = input("Enter the answer for the noun2 blank space:");
answers['noun2'] = answerInput

##Get the input for the noun3
answerInput = input("Enter the answer for the noun3 blank space:");
answers['noun3'] = answerInput    

##Get the input for the animal
answerInput = input("Enter the answer for the animal blank space:");
answers['animal'] = answerInput

##Dislay the answers

print ("\t\t\tSPRING GARDEN\n" +
       "\tPlanting a vegetable garden is not only fun, \n" +
       "it also helps save " + answers['pluralNoun'] + ". You will need a piece \n" +
       "of " + answers['adjective'] + " land. You may need a " + answers['noun'] + " to keep \n"
       "the " + answers['pluralNoun2'] + " and " + answers['noun2'] + " out. As soon as \n" +
       answers['noun3'] + " is here you can go out there with your " + answers['animal'] + "\n" +
       "and plant all kinds of " + answers['pluralNoun'] + ". Then in a few \n" +
       "months, you will hav corn on the " + answers['noun2'] + " and big, \n" +
       answers['adjective'] + " flowers.\n" +
       "\t\tTHE END")
