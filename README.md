# buildingU_React_Lesson_Exercise
These are the instructions for this exercise.

## Prerequisites
- Completed both JavaScript lessons.
- Node.js and NPM installed.
- Git installed

## Objective
Demonstrate your understanding of various React hooks through a series of challenges. Each challenge will focus on a specific hook, and the final challenge will incorporate multiple hooks. Use this exercise to explore how React hooks can be used together to build dynamic forms and UI elements.

## Instructions
### Step 1: Download the Project
1. Download the project as a zip file from the [repository](https://github.com/dBish6/buildingU_React_Lesson_Exercise) and extract it to your desired location. **Do not clone** the repository since you're not contributing to it.
2. Open the project directory in your preferred code editor or IDE.

### Step 2: Set Up the React App
Navigate to the project directory if needed and install the dependencies:
```
$ cd your-project-directory
$ npm install
```
### Step 3: The Challenges
Each challenge focuses on demonstrating the concept of each hook except the final challenge where you can use however many hooks you want. You will find the challenges in the src/components directory.
- Each file is named according to the hook it demonstrates.
- Read the comments inside each challenge file for what you have to complete.

Here are the challenges you'll be working on:
1. **Hook Challenges:**
   - `1.UseStateChallenge.jsx`: Demonstrate the use of `useState`.
   - `2.UseRefChallenge.jsx`: Demonstrate the use of `useRef`.
   - `3.UseEffectChallenge.jsx`: Demonstrate the use of `useEffect`.
   - `4.useContextChallenge`: A directory to mimic the idea of the context being used somewhere else in the project; containing AuthContext.jsx and UseContext.jsx for demonstrating useContext.
   - `5.UseReducerChallenge.jsx`: Demonstrate the use of `useReducer`
   - `6.UseMemoChallenge.jsx` (Optional): Show how `useMemo` can optimize performance.
2. **Final Challenge:**
   - The `7.FinalChallenge.jsx` will be a form that incorporates multiple hooks to manage form data, validation, and real-time feedback.

### Step 5: Running the Challenges
The project is set up so you can run each challenge separately using npm scripts. Use the following commands in the terminal to start each challenge (e.g., npm run dev:useState):

```
$ npm run dev:<hook name>
```

**Available Scripts:**
- `dev:useState`
- `dev:useRef`
- `dev:useEffect`
- `dev:useContext`
- `dev:useReducer`
- `dev:useMemo` (Optional)
- `dev:final` (Final Challenge)

## Bonus!
Instead of using npm scripts like I mentioned to navigate between challenges, you can implement client-side routing using [`react-router-dom`](https://reactrouter.com) to create a page for each challenge. This will require modifying `App.jsx` to include route paths for each challenge and use the component as a page.

If you decide to implement routing, you can delete the individual challenge scripts from the `package.json` and only use the `"dev"` script to run the app.
