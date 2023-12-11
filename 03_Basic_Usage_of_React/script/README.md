Let's continue to learn the basic use of React.

First off, we need to install React. You can do this by running the command: `npm i react react-dom`. This command installs two packages. react is the React core, which provides functions for creating elements and components. react-dom handles dom operations. Simply put, react creates elements, and react-dom brings them into the page.

Now, let's switch to VSCode to install these packages. Assuming you have a basic directory structure with a simple HTML page and a package.json file, right-click on the folder and open the integrated terminal. Type `npm i react react-dom` to install both packages. After a brief pause, you'll have the packages installed. You can double-check this in your package.json file.

So, we have React installed. But how do we use it? Let's go through the steps together.

- Step 1: Import the `react` and `react-dom` JavaScript files. Remember, `react` comes first, then `react-dom`.
- Step 2: Create a React element using the `React.createElement` method. Don't worry about the parameters for now, we'll discuss those later. Just remember that `React` is provided by the `react.development.js` file.
- Step 3: Render the created React element to the page using the `ReactDOM.render` method. `ReactDOM` is provided by the `react-dom.development.js` file. Please pay attention to capitalization when typing these.

So, these are the three basic steps to use React.

Ready to move from theory to practice? Let's go back to the code and do it ourselves.

Starting with the first step: importing the necessary JavaScript files. We can do this directly using the `script` tag. From the current `node_modules`, we'll import `react`, then `umd`, and finally `react.development.js`. Essentially, we first import the `react.js` file, and then the `react-dom` file, or in other words, `react-dom.development.js` file. [pause] In this way, we have successfully imported the two JS files we need.

Next, we'll tackle the second step: creating a React element. We'll use the `React.createElement` method for this. This method requires three parameters. The first is the name of the element you want to create, which corresponds to the name of an HTML element. For example, if you want to create a heading, you would write `h1` here. The second parameter is for the attributes of the element. If you want to add attributes to this element, you can write them here. If there are no attributes, you can simply write `null`. For now, let's keep it simple and go with `null`. The third parameter is the node or child node of the element, which can be a text node or an element node. To keep it simple, we'll write a text node, say, `Hello React!`. By using this method, we can create a `React` element. Finally, we'll declare a variable to store the React element we've created. Now, the second step is done.

Moving on to the third step, we're going to render our React element. But how do we do that? We'll use the `ReactDOM` object, which conveniently provides us with a `render` method. This method takes two parameters. The first one is the React element we want to render. In our case, it's the title we just created. So, we'll put the title here.

The second parameter is where we want to render our element on the page, also known as the mount point. Here, we're going to use `document.getElementById` to get a DOM object with an `id` of `root` from our page. But wait, we don't have a `root` element on our page yet, do we? Therefor, we need to manually create an element with an id attribute of `root`.

At this point, we have completed the three steps of basic use of React.

Finally, let's open this page to check if our element was successfully created and rendered. [pause] We can see that `Hello React!` is displayed correctly on our webpage. Great!

We can also inspect the element by opening the developer tools. We find that an `h1` element has been created and placed inside the element with `id` of `root`. Look at this `h1` tag, it has a text node but no attributes. This matches the parameters we passed to `React.createElement` earlier: we created an `h1`, without attributes, with a text node.

So, this is the most basic use of `React`.

Finally, let's summarize the whole process. First, you must have `React` to use it, so we need to install the react and react-dom packages through the command line. Next are the usage steps. The first step is to import the js files, please pay attention to the order of import. The second step is to create a react element. How do we create it? We create it through the `React.createElement` method, please pay attention to case sensitivity. Okay, the third step is to render the React element. How do we render it? We use the `ReactDOM.render` method to render the react element we created earlier to the page. That's it.

Alright, that's all for the most basic use of React.

Thank you for watching, remember to like and subscribe to my channel, see you in the next lesson.
