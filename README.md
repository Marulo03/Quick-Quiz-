# Quick-Quiz-
This is my first project in Python, im still learning but i will upload every project here on github

#Quiz game in Python



print("Welcome")

playing = input("Do you want to play ")     #We start with this input, that allows the user put information

if playing != "yes":        #!= means if its not equal to yes, then quit the program.
    quit()

print("Okay, then Let's play ")

score = 0       #We create score, this score will define your results on the quiz

answer = input("Who create Python? ")   #We put an input, so the user can answer the question

if answer.lower() == "guido van rossum":    #Here me do the statement, that is the key in all the code.
    print("Correct")
    
else:
    print("Incorrect")
score += 1              #This is the score, that is adding 1 point for each question you answer correct

answer = input("What is the most demanding programming language? ")

if answer.lower() == "javascript":      #We put the method lower, so the user can type the answer in capitals without a problem
    print("Correct")
    
else:
    print("Incorrect")
score += 1

answer = input("Who create Microsoft? ")

if answer.lower() == "bill gates":
    print("Correct")
    
else:
    print("Incorrect")
score += 1

answer = input("Who create Facebook ")

if answer.lower() == "mark zuckerberg":
    print("Correct")
    
else:
    print("Incorrect")
score += 1

answer = input("Who create JavaScript? ")

if answer.lower() == "brendan eich":
    print("Correct")
    
else:
    print("Incorrect")

score += 1

print("You got "  + str(score) +  " questions correct") #Here we use str, so we can convert the score into a string
print("Your score is " + str((score/5) * 100) + "%.")   #Here we are getting the percentage of our test

#So we got the number of questions we answer right and the percentage
