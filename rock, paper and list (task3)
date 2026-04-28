import random
user_score = 0
comp_score = 0
while True:
    print("\n Rock Paper Scissor")
    print("1. Rock")
    print("2. Paper")
    print("3. Scissors")
    user = input("Enter your choice (1/2/3): ")
    if user == "1":
        user_choice = "rock"
    elif user == "2":
        user_choice = "paper"
    elif user == "3":
        user_choice = "scissors"
    else:
        print("Invalid input")
        continue
    comp_choice = random.choice(["rock", "paper", "scissors"])
    print("You chose:", user_choice)
    print("Computer chose:", comp_choice)
    if user_choice == comp_choice:
        print("it is a tie")
    elif user_choice == "rock" and comp_choice == "scissors":
        print("You win")
        user_score = user_score + 1
    elif user_choice == "paper" and comp_choice == "rock":
        print("You win")
        user_score = user_score + 1
    elif user_choice == "scissors" and comp_choice == "paper":
        print("You win")
        user_score = user_score + 1
    else:
        print("Computer wins")
        comp_score = comp_score + 1
    print("Score -> You:", user_score, "Computer:", comp_score)
    again = input("Play again? (yes/no): ")
    if again != "yes":
        print("Game over")
        break
