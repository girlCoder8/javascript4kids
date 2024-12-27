### Project 3: Quiz App

#### Objectives
- Build a simple quiz app with multiple questions.

#### Code Example
```javascript
let questions = [
  { question: "What is 2 + 2?", answer: "4" },
  { question: "What is the capital of France?", answer: "Paris" },
];

questions.forEach((q) => {
  let userAnswer = prompt(q.question);
  if (userAnswer.toLowerCase() === q.answer.toLowerCase()) {
    console.log("Correct!");
  } else {
    console.log("Oops, the correct answer is " + q.answer);
  }
});
```