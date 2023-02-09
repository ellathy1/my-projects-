import random

def get_choices():
  player_choice = input("Enter a choice (rock, paper, scissors)\n")
  options = ["rock", "paper", "scissors"]
  if player_choice not in options:
    print("Invalid choice. Please enter rock, paper, or scissors.")
    player_choice = input("Enter a choice (rock, paper, scissors)\n")
  computer_choice = random.choice(options)
  choices = {"player": player_choice, "computer": computer_choice}
  return choices

def check_win(player, computer):
  print(f"You chose {player} computer chose {computer}")
  if player == computer:
    print("It's a tie!")
  elif player == "rock" and computer == "paper":
    print("paper cover rock. you lose.")
  elif player == "rock" and computer == "scissors":
    print("rock break scissors. you win!")
  elif player == "paper" and computer == "scissors":
    print("scissors cut paper. you lose.")
  elif player == "paper" and computer == "rock":
    print("paper cover rock. you win!")
  elif player == "scisssors" and computer == "rock":
    print ("rock break scissors. you lose.")
  elif player == "scissors" and computer == "paper":
    print("scissors cut paper. you win!")

choices = get_choices()
check_win(choices ["player"],choices["computer"])
