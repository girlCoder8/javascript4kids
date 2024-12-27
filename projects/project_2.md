### Project 2: Rock-Paper-Scissors Game

#### Objectives
- Build a game using all learned concepts.

#### Code Example
```javascript
let choices = ["rock", "paper", "scissors"];
let playerChoice = prompt("Choose rock, paper, or scissors:");
let computerChoice = choices[Math.floor(Math.random() * choices.length)];

if (playerChoice === computerChoice) {
  console.log("It's a tie!");
} else if (
  (playerChoice === "rock" && computerChoice === "scissors") ||
  (playerChoice === "scissors" && computerChoice === "paper") ||
  (playerChoice === "paper" && computerChoice === "rock")
) {
  console.log("You win!");
} else {
  console.log("Computer wins!");
}
```