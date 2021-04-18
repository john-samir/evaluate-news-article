## Would you rather game

Would you rather game is a well known game that allows the user to answer questions with two options.

This tool is implemented using React for UI, Router and Redux for state management. 
the backend simulator of this tool is provided by Udacity team.

## Notes

1. to be able to use this tool, you have to run below commands that will install all project dependencies and will run the game
```
npm install
npm start
```

2. This web tool is simply consists of multiple pages as follows: 
- **Sign In:** The user can login in order to play the game.
- **Home Page:** Where you can see all Polls/Questions (un-answered, answered).
- **Poll Details:** Where you can either answer the Poll (if not answered) or see your answer with a comparison of all users votes/answers, percentage, ..etc.
- **New Question:** Where you can add a new question/Poll.
- **Leaderboard:** where you can see the ranking of all users based on the number of answered polls and the number of polls created by each user.

3. Below are all available functionality:
- Login, Logout
- Create New Poll
- Answer Polls
- See Leaderboard 
- See answered, unanswered polls

## React Components
```
- App
- Dashboard
- Leaderboard
- Loading
- Nav
- NewQuestion
- Poll
- PollDetails
- SignIn
```

## Middlewares
```
- logger: this is used to log every action with it's new state.
- index: this is used to configure all middlewares (thunk, logger) 
```

## Reducers
```
- authedUser: handles all actions related to authed user (SET_AUTHED_USER).
- users: handles all actions related to users (RECEIVE_USERS, ADD_QUESTION_TO_USER, ADD_QUESTION_ANSWER_TO_USER).
- questions: handles all actions related to questions (RECEIVE_QUESTIONS, ADD_QUESTION, ADD_QUESTION_ANSWER).
- index: combine all reducers (authedUser, users, questions).
```

## Actions
```
- authedUser: contains all action functions that handle authed user (setAuthedUser, handleSignIn, handleSignOut).
- users: contains all action functions that handle users (receiveUsers, addQuestionToUser, addQuestionAnswerToUser).
- questions: contains all action functions that handle questions (receiveQuestions, handleAddNewQuestion, handleSubmitQuestionAnswer).
- shared: handle shared actions (handleInitialData).
```

## Copyrights

This game is implemented by **John Ghabrial** using an API file that was given by Udacity team as part of a project for **"Front End Web Development Advanced Nanodegree Program"** course.
