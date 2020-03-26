### Remember

Answer these on your own, then compare answers as a group

1.  What is React? It is a javascript library used to build user interfaces for web applications.

2.  What is create-react-app? tool/command that configures a bare-bones react-app for you.

3.  What is Component Based Architecture? breaks down a design into functional and logical components within one another. In this way, these components become self-sustaining, independent micro-systems

4.  What is JSX? language similar to HTML used within our javascript code

5.  What is the virtual DOM? a stored ideal version of a UI that is not currently present on the DOM

6.  What is unidirectional (one-way) data flow? data can go from a parent component to a child, but not vice-versa. However, events can travel upwards on the chain.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

9.  Explain what this code does:

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

10.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
