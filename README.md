# JourneyWithReact

# Learnings 📖
### Day 1
#### Topics Covered:

- What is React and Why Use It

- Basics of React Components

- Introduction to Hooks, States, and Props
- JSX Fundamentals
<br> <br>

### Day 2 
#### Topics Learned : 
 - Use Effects in react  
 - UseRef hooks in react (uses for component to remember some information witout triggering new renders ) 
 
 <br>
  
 ```
  const number = useRef(0);
  useEffect(() => {
    number.current = number.current + 1;
    console.log(`The current number is ${number.current}`);  
  }, [count] ); 
  

  // Count is a component on which when clicked run the useEffect function ;
 ```
 
- [Learned Conditional Rendering](https://react.dev/learn/conditional-rendering) 

#### New Discoveries:

- VS Code Extension: Found `ES7 React/Redux/GraphQL/React-Native Snippets`, a useful VS Code extension to streamline the development process!

# Resources 📌
 - [Code with Harry - Sigma Web Development Course](https://www.youtube.com/watch?v=bio2eP5YXyw&list=PLu0W_9lII9agq5TrH9XLIKQvv0iaF2X3w&index=108)
 - [React.dev documentation](https://react.dev/learn/)
 - [React.dev Official Documentation](https://react.dev/learn)
