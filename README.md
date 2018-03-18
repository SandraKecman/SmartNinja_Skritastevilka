secret=24
guess=int(raw_input("Guess secret number between 1 and 30:"))

if guess==secret:
    print "Congratulation! The secret number is 24."
else:
    print("Sorry, that's not a secret number try again")
