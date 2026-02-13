# game_score.py

# Input collection
player_name = input("Enter player name: ")

# Numeric input processing
games_played = int(input("Enter number of games played: "))

# Score data entry
total_score = int(input("Enter total score achieved: "))

# Computation
average_score = total_score / games_played

# Output display (match required format)
print("\nPlayer:", player_name)
print("Games Played:", games_played)
print("Total Score:", total_score)
print("Average Score:", average_score)
