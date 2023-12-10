Welcome to our journey into the basics of React.

First off, we need to install React. You can do this by running the command `npm i react react-dom`. This command installs two packages. `react` is the React core, which provides functions for creating elements and components. `react-dom` handles DOM operations. Simply put, `react` creates elements, and `react-dom` brings them to life on the page.

Now, let's switch to VSCode to install these packages. Assuming you have a basic directory structure with a simple HTML page and a `package.json` file, right-click on the folder and open the integrated terminal. Type in `npm i react react-dom` to install both packages. After a brief pause, you'll have the packages installed. You can double-check this in the `package.json` file.

So, we've installed React. But how do we use it? Let's walk through the steps together.

1. Import the `react` and `react-dom` JavaScript files. Remember, `react` comes first, then `react-dom`.
2. Create a React element using the `React.createElement` method. Don't worry about the parameters for now, we'll get to those later. Just remember that `React` is provided by the `react.development.js` file.
3. Render the created React element to the page using the `ReactDOM.render` method. `ReactDOM` is supported by the `react-dom.development.js` file. Keep an eye on the case when typing these.

These are the three basic steps to use React. Ready to put theory into practice? Let's jump back into the code and start coding.
