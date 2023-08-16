# reading-notes
Code 301 - Intermediate Software Development
<h2>Class 01</h2>
Component-Based Architecture

What is a “component”? In React, a component is a reusable piece of the user interface (UI). Think of it as a building block or a widget. Each component is responsible for rendering a part of the UI and can have its own state, logic, and rendering methods. Components can be combined and nested within other components to build more complex UIs. What are the characteristics of a component? Reusability: Components are designed to be reusable. For example, a button component can be used in multiple places across an application.

Encapsulation: Components encapsulate their own logic, structure, and presentation. The internal workings of a component are hidden from the outside world.

State: Class-based components (and function components using hooks) can maintain their own state. State is a way to store information that can change over time and affect the component's render output.

Props: Components can receive inputs, called "props", from their parent components. Props are read-only and help components communicate with each other.

Lifecycle Methods: Class-based components in React have lifecycle methods that get executed at different stages of a component's life, such as when it's mounted to the DOM or updated.

Render Method: Every React component has a render method (or its equivalent in function components) that returns what should be displayed on the screen.

Composability: Components can be nested within other components, enabling the creation of complex UIs from simpler building blocks.

What are the advantages of using component-based architecture? What is Props and How to Use it in React

What is “props” short for? Props stand for properties and is a special keyword in React Props are being passed to components like function arguments Props can only be passed to components in one way (parent to child) Props data is immutable (read-only)

How are props used in React? What is the flow of props? - Top-Down/Unidirectional:

##Class 02
What can you put inside props?

Props are like little gifts or packages you pass between components. Inside these packages, you can have:

Basic stuff like words (strings), numbers, true/false values (booleans). Lists (arrays) or more complex packages (objects). Actions or tasks (functions) that you want a component to do. Even other React components, like little pre-made blocks you've built! What's the difference between props and state?

Think of props and state like this:

Props: They're like instructions given to a toy (component). You can't change the instructions once you've given them. State: It's like a toy's internal battery-powered mechanism. The toy can change its own state (like switch on/off, move faster/slower), but you, as someone playing with it, can't directly change it. When does our app redraw or refresh itself?

Imagine your React app as a drawing. Sometimes parts of the drawing need a little update. This happens when:

You change the inner workings or state of a component. You give new instructions (props) to a component. The bigger picture (parent) updates, which might cause the smaller parts (children) to update too. Some special actions or conditions can also force a refresh. What are some examples of things we can keep in state?

State is like a component's personal diary. Here are things you can jot down in it:

Info from forms: like what you type, which boxes you tick. Whether to show or hide something: like a popup or dropdown menu. Data from the internet: like a list of movies or songs. User choices: like which tab they've clicked on or the volume level of a video.


Class 03
