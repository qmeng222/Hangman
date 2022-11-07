# Study Notes: React Hooks

Reference:
React Hooks Simplified https://courses.webdevsimplified.com/react-hooks-simplified

## Fundamentals

- npm (node package manager)
- npm is the default package manager for the JavaScript runtime environment Node.js
- What is a Hook? A Hook is a special **function** that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.
- When would I use a Hook? If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component.
- we can only use hooks inside functiton components (cannot use them in class components)
- React hooks must be called in the exact same order in evry component render (cannot put React hooks inside if statements or functions or loops, they cannot nest in anything, they must be at the top level)

## Must Know Hooks

1. useState

   ```
   const [count, setCount] = useState(6);
   ```

   - the first item in array(count): the current state
   - the second item in array (setCount): the function that allows you to update the current state
   - 6 is a default value in this case

2. useEffect
3. useContext

## Lesser Used Hooks

## Optional Hooks

## Custom Hooks
