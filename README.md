# Timer Challenge Project

### Overview:

The Timer Challenge web app is a game built with React where players aim to stop a timer as close to a target time as possible. The closer the player stops the timer to the target time, the higher their score. This app uses React Functional Components (RFCs) and React Portals to manage its user interface and provide a seamless, interactive gaming experience.

### Features

#### 1. Timer Display:

- Displays a countdown or count-up timer.
- Players try to stop the timer as close to a predefined target time as possible.

#### 2. Start and Stop Controls:

- A button to start the timer.
- A button to stop the timer.

#### 3. Score Calculation:

- Calculate the player's score based on how close they stop the timer to the target time.
- Display the score after each attempt.

#### 4. High Scores:

- Track and display the highest scores.
- Maintain a leaderboard of top scores.

#### 5. React Portals for Modals:

- Use React Portals to display modals for game instructions, scores, and other pop-up information.
- Ensure modals are rendered outside the main DOM hierarchy for better control and styling.

#### 6. User Interface:

- A clean and intuitive UI that guides the player through the game.
- Responsive design to ensure a good experience on both desktop and mobile devices.

#### 7. State Management:

- Use React's useState and useEffect hooks to manage the timer state and game logic.
- Use React Context or a state management library like Redux for global state management if needed.

### Installation Steps:

This command will install all the necessary dependencies.

```
npm install
```

This command will start the devlopement server.

```
npm run dev
```

### Output:

The page of the challenge where you enter your name and pick the challenge which you like to face.

![timer homepage](https://github.com/Rexon-Pambujya/timerChallenge/blob/main/images/Image1.png)

The dialog or pop up which displays your score.
![score dialog](https://github.com/Rexon-Pambujya/timerChallenge/blob/main/images/Image2.png)

Thank you for going through my project.
