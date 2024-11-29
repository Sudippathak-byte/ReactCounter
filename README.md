
This is a simple counter application built using React. The app allows users to increment and decrement a counter value, demonstrating basic React functionality and the use of hooks for state management.


What Hooks I Have Used
useState:
This hook is used to create a state variable (counter) and a function to update it (setCounter).
It allows the counter value to be dynamically updated when the user clicks the buttons.

How It Works
The counter starts with an initial value of 15.
When the "Add Value" button is clicked:
The counter increases by 1 using the setCounter function.
When the "Remove Value" button is clicked:
The counter decreases by 1 using the setCounter function.



Key Features
Dynamic State Management: The app uses the useState hook to manage the counter's value.
Real-Time Updates: The UI updates immediately when the state changes.

javascript

let [counter, setCounter] = useState(15); // Initializes state

const addValue = () => {
  setCounter(counter + 1); // Increments counter
};

const removeValue = () => {
  setCounter(counter - 1); // Decrements counter
};



Why I Made This
As a fresher learning React, this project helped me:

Understand how React works.
Practice using the useState hook.
Build a functional and interactive app from scratch.


![Screenshot 2024-11-29 201721](https://github.com/user-attachments/assets/725b76ad-8d0a-478d-b973-21eafcbd90e2)
