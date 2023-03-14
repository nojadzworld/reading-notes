# State and Props

## React lifecycle

1.Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
**render**
2.What is the very first thing to happen in the lifecycle of React?
**Mounting/Constructor**
3.Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
**Constructor, render,componentDidMount,React Updates, componentWillUnmount**
4.What does componentDidMount do?
**If you need to load anything using a network request or initialize the DOM, it should go here.**

## React State Vs Props

1.What types of things can you pass in the props?
**things that we want our component to do**
2.What is the big difference between props and state?
**props are passed into a component and state is handled within the component**
3.When do we re-render our application?
**when we change the state of it**
4.What are some examples of things that we could store in state?
**something that would get updated at some point**