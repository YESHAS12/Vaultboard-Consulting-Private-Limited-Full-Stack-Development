# Vaultboard-Consulting-Private-Limited-Full-Stack-Development
LCM Monster Hunt

An interactive, educational game to teach LCM (Least Common Multiple) to children (grades 4–7) in a playful and engaging way.

Players solve LCM problems by selecting the correct answer, and scores are tracked on a live leaderboard.

📌 Features

Interactive LCM game with random numbers.

Selectable answers via buttons for kid-friendly interaction.

Cumulative scoring: the same player’s score updates if they play multiple rounds.

Player name is stored and displayed until changed.

Option to change player name anytime.

Live leaderboard displaying top scores.

Reset leaderboard clears all scores and the current player name.

Friendly alerts for correct/incorrect answers.

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: PHP

Server: XAMPP (Apache + PHP)

Data Storage: JSON files (leaderboard.json for scores)

📂 Project Structure
lcm_game/
├─ index.php                  # Main game page
├─ update_leaderboard.php     # Updates the leaderboard with correct answers
├─ leaderboard_display.php    # Returns the leaderboard HTML for live updates
├─ reset_leaderboard.php      # Resets the leaderboard
├─ leaderboard.json           # Stores leaderboard data
└─ README.md                  # Project documentation

🚀 How to Run Locally

Install XAMPP (https://www.apachefriends.org/index.html
).

Start Apache via XAMPP Control Panel.

Place the project folder in htdocs:

C:\xampp\htdocs\lcm_game


Open your browser and navigate to:

http://localhost/lcm_game/index.php


Enter your name when prompted and start playing!

🎮 How to Play

Click Start Game to generate a new LCM question.

Select the correct answer from the buttons displayed.

If correct, your score increases by 1.

If incorrect, the correct answer is displayed in an alert.

You can change player name anytime using Change Player.

To reset the leaderboard and current player, click Reset Leaderboard.

🧠 Notes for Developers

Leaderboard Storage: leaderboard.json is a simple JSON file storing player names and scores.

Score Updates: update_leaderboard.php adds 1 point for correct answers; cumulative for repeated plays by the same player.

Live Updates: leaderboard_display.php fetches the latest leaderboard without reloading the page.

Reset Leaderboard: reset_leaderboard.php clears all scores and works with JS to clear the player display.

⚡ Future Enhancements

Add multiple difficulty levels with bigger numbers.

Add animations for correct/incorrect answers.

Add sound effects for more interactive experience.

Support HCF or Algebra mini-games alongside LCM.
