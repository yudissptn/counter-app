Learn basic react application by built shopping cart app that commonly used by e-commerce
1. Crete react-app, start react-app, install library (development server, webpack and babel) and install bootstrap and import it to file.
2. Understanding what classes are, how to use them and render method that use markup which is using jsx sintax.
3. Create components and import react component. And import components to index.js file
4. Understand how babel compile jsx to element
5. Assign App.js as a parent component while Navbar.jsx and Counter.jsx as child component while Counters.jsx as child of Counter.jsx component
6. Create state with counters prop inside App.js which is accessible in it's child components
7. Create methods to handle application function inside App.js to increment, reset and delete elements.
8. Use higher order function(map) to display elements based on counters props object inside App.js in Counters.jsx
9. Call Counter component inside Counters.jsx to arrange css bootstrap classess for dynamic element display.
10. Create Navbar.jsx as stateless function components. And call it in App.js, also defined totalCount to use filter method to check length of counters props that has a value grater than 0 to showing on the page, number of the product that has been added
11. To understand which app that rendered first, create a lifecycle hooks methods, such as constructor in App.js before render method. This lifecycle hooks will be called first when the app running.
12. In every render methods inside all component, use console.log to print 'componentName-rendered' to show rendered order of the components. This shown that render method called after the constructor component.

