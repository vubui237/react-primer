# Welcome to React

## Introductory Thoughts
### Angular vs React
Open the directory called angular-vs-react/. Live-serve the index of this app. Let's take a look at the code for both of these apps, as well as the element inspector, so that we can see how they're updating the DOM. 

### Why React?
As we saw in the comparison above, there are a few reasons to use React. I'd list the following as pretty good reasons for switching from AngularJS to React: 
- Virtual DOM and Updates to the DOM
- Component Architecture
- Emphasis on JavaScript

### Learning a New Framework or Library
Of course, learning a new library or framework comes with some difficulties. Try to remember how hard it was to learn jQuery or Angular, how strange the syntax seemed, how hard it was to master every step of the process. 

Now get ready to go through some of that pain again.

But the benefits are huge, and the process is necessary, as our frameworks will change al of the time. 


### A Few Hurdles
We're going to tackle each of these as we build, but just so we know what we're up against, here are a few potential roadblocks for us to overcome: 
- ES6, Babel, and Webpack
- Manual Bootstrapping
(Actually, create-react-app will take care of these first two for us.)
- Classes and Inheritance
- Components
- Component State
- Parent & Child Components and Props
- Unidirectional Data Flow
- Event Handling

## React Under the Hood
Technically, you don't need to understand a lot of what follows (well, Babel and Webpack, at least) in order to use React. But you should at least have some exposure to them before you start relying on create-react-app to take care of them for you. 

### JSX
- Purpose
- Benefits
- Caveats

### Babel
- Purpose
- Core and Presets
- .babelrc

### Webpack
- Comparison with Gulp
- Difficult Syntax
- Why you need to see it (and not understand it)

## A Look at Our First App
First, let's build our own React app, without help from create-react-app. Why? Well, you know what Emerson wrote: "The man who built for himself a chariot lost the use of his legs." Or I just want you to suffer and appreciate create-react-app--I'm not sure. 

Open the first-react-app folder and check out the  file structure:

-- build/
  -- index.html
-- src/
  -- index.js
-- webpack.config.js
--.babelrc

We'll talk about each of these files and then we'll use them to build our app.

I've provided the webpack and babel config for you, but you'l need to install the depenedncies. Just run yarn.

### A Few Things to Note
- Importing (requiring) React and ReactDOM
- Selecting the DOM element
- Rendering the app with ReactDOM.render()

### Alter the App
Get something else to render on the page. Make your own heading.

### Adding More JSX
Now let's add some more JSX to the app. 
1. Substitute the html string for a JavaScript expression. (Both of these are JSX elements, which are then converted to JavaScript.)

2. Write a function to return a larger JSX element (Should be done in a new file called App.js using imports and exports);

3. Write a condition to return one of two JSX elements. (Do this in your App.js file);

## Our Second App
Now let's build another app. Shut down your previous app and navigate to second-react-app. 

I've provided the webpack and babel config for you, but you'l need to install the depenedncies. Just run yarn. 

For your reference, you'll install the following dev dependencies: 
- react
- react-dom
- babel-core
- babel-loader
- babel-preset-env (gets latest ES6)
- babel-preset-react
- style-loader
- css-loader

Now follow the steps beginning in the index.js file. These steps will lead you through the following actions:

1. Bootstrapping the react app
2. Adding styles
3. Importing and writing the App component
   * Writing functional components
   * Rendering child components
4. Importing and writing the UserInput component 
   * Writing class components
   * Setting up state
   * Re-rendering on state changes
   * Receiving user input and changing state

## If we have time...
If we finish all of that, we'll use create-react-app to install and start a react app. Then we'll practice writing class components and using component state. 
