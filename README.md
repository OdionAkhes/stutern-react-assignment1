==> Question 2
List five significant features of React

1.
Component-Based Architecture: React is built on a component-based architecture where the entire UI is broken down into smaller components, making it easier to manage and maintain large codebases. Each component is independent and can be reused across multiple applications.

2.
Virtual DOM: React uses a Virtual DOM (Document Object Model) which is an abstraction of the actual DOM. This enables React to efficiently update the UI by only rendering the components that have changed, rather than re-rendering the entire page.
3.

JSX: React uses JSX (JavaScript XML) which is a syntax extension to JavaScript that allows developers to write HTML-like code within their JavaScript files. This makes it easier to write and understand the UI code.
4.

Unidirectional Data Flow: React follows a unidirectional data flow pattern where data flows from the parent component to its child components. This makes it easier to debug and maintain the code as changes to the data are predictable and easy to trace.
5.

Redux: Redux is a popular state management library that works well with React. It provides a centralized store for the application's state, which can make it easier to manage and update the state across different components.

.

Tooling: React has a rich set of developer tools, such as the React Developer Tools browser extension and the Create React App command-line tool, which can help developers build and debug applications more efficiently.


==> Question 3
Advantages of React
1.
Better Code Organization: React's component-based architecture encourages developers to organize their code into modular and reusable components, which can make it easier to maintain and scale the application.
Faster Development Time: React's efficient updates to the user interface can save development time, especially when building complex applications with many components.

2.
Easy to Learn: React has a simple and straightforward API that is easy to understand and learn. Additionally, the component-based architecture of React makes it easy for developers to build reusable UI components.
3.

Cross-Platform Development: React can be used to build applications for the web, mobile, and desktop platforms, which can save development time and resources.
4.

Declarative Programming: React uses a declarative programming model, which makes it easier to reason about the application's behavior and state. Developers can focus on the "what" of the application rather than the "how," which can lead to simpler and more readable code.
5.

Strong Performance: React's virtual DOM and efficient updates can lead to improved performance and a smoother user experience.

.
Strong Community and Ecosystem: React has a large and active community of developers and a robust ecosystem of tools and libraries. This means that developers can benefit from the collective knowledge and resources of the community and can find solutions to problems more easily.


==> Question 4
What is the name of the Software Engineer that created React? Also, which company owns React?

React was created by Jordan Walke, a software engineer at Meta. 
React is an open-source JavaScript library, and it is owned and maintained by Meta4

==> Question 5
1.
Syntax: HTML uses angle brackets < > to wrap around its elements, while JSX uses curly braces { } to wrap around its elements.

2.
Attributes: In HTML, attributes are defined using the syntax attribute="value", while in JSX, attributes are defined using the syntax attributeName={value}.

3.
Class and Style Names: In HTML, class names are defined using the class attribute, while in JSX, class names are defined using the className attribute. Similarly, in HTML, style attributes are defined using the style attribute, while in JSX, style attributes are defined using an object syntax.

4.
Comments: In HTML, comments are wrapped in <!-- -->, while in JSX, comments are wrapped in {/* */}.

5.
Tag Names: In HTML, tag names are case-insensitive, while in JSX, tag names must be capitalized. For example, in HTML, <div> and <DIV> are equivalent, while in JSX, only <Div> is considered valid.

6.
Conditional Rendering: JSX allows for conditional rendering, meaning different components or HTML can be rendered based on conditions or user input, while this cannot be done with HTML alone.


==> Question 6 
Why can’t browsers read JSX?

JSX is a syntactic extension of JavaScript that allows developers to write HTML-like syntax to describe the structure and appearance of their UI components.

Browsers cannot read JSX because JSX is not valid JavaScript code and Before a browser can render JSX, it needs to be transformed into valid JavaScript code. This transformation is usually done using a tool called a transpiler called Babel, which converts the JSX code into plain JavaScript that the browser can read and understand.

React provides its own built-in transpiler, called Babel, which can be used to convert JSX into JavaScript. The transpiled JavaScript code is then sent to the browser, where it can be executed and rendered.























# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
# stutern-react-assignment1
