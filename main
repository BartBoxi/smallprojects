import random

def rockPaperScissors()-> str:
    counter = [0,0]

    options = ("rock", "paper", "scissors")
    winning_moves = {
        "paper" : "rock",
        "rock" : "scissors",
        "scissors" : "paper"
    }
    while counter[0] < 3 and counter[1] < 3:
        users_input = input(str("What is your option? (rock, paper, or scissors)?"))
        computer_choice = random.choice(options)
        if users_input not in ["rock", "paper", "scissors"]:
            print(f"Invalid choice.")
            continue
        elif users_input == computer_choice:
            print(f"There is a draw with {computer_choice}")
        elif winning_moves[users_input] == computer_choice:
            print(f"Well done. The computer chose {computer_choice} and failed")
            counter[0] += 1
        else:
            print(f"Sorry, but the computer chose {computer_choice}")
            counter[1] += 1
    False
    if counter[0] == 3:
        return f"User is the winner"
    else:
        return f"Computer is the winner"

print(rockPaperScissors())


