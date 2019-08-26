# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications==true
- React will only render on the server using Node.js== false
- React is a full stack framework for modern web applications==false its a library
- React is a flexible library that plays the role of V in an MVC framework==true
- You should always update a component's state directly using this.state==true: false you may use this.setState and props 
- React is made up of encapsulated components that manage their own state==false : true One of the great things about React’s function components is that they’re declarative. Instead of forcing you to update the DOM step by step, function components let you say “I want these props to result in this element” – and then it’s all good!
- 
- React components render HTML==true you can add a DOM file to React. (DOM) is a programming API for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated.

1b. Add an interesting true fact about React to the list.
React is helpful but difficult.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: smart components are also known as parent components that pass down traits to the child or dumb components from which they inherit those traits.

  Researched answer: Smart components, are the ones that keep track of state and care about how the app works. ... The root component off an app is a good example of a smart component.
  
  Smart components are app level components that perform functions and manage data while dumb components focus solely on the UI.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: i dont recall using yarn add but i know that yarn install installs a package that updates files so react will work.

  Researched answer: yarn add react will install the react package from the npm registry.



4. How would you explain state to a friend who doesn't know code?

  Your answer: database that holds the certain state of the blueprint 

  Researched answer: "State just means storing some value or values. In contrast, something that is stateless does not store any values between point in time A and point in time B." - Reddit Person



5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer:component state is the original value for your class and props is what is used when refering back to your original state value.

  Researched answer: The difference is all about which component owns the data. State is owned locally and updated by the component itself. Props are owned by a parent component and are read-only. Props can only be updated if a callback function is passed to the child to trigger an upstream change.
