### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

A Javascript library used to simplify website building by utilizing a component based architecture.

2.  What is create-react-app?

A command to download all necessary react files so that the user does not need to build an app from the ground up.

3.  What is Component Based Architecture?

Creating a program using multiple reusable pieces.

4.  What is JSX?

A type of Javascript that looks similar to HTML, but is read differently, able to be used with React.

5.  What is the virtual DOM?

React uses this to make changes virtually before requiring the user's machine to render unnecessary changes.

6.  What is unidirectional (one-way) data flow?

Data flows down from the parent to its children.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

9.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

14. Compare and contrast one-way data flow with two-way data binding.
