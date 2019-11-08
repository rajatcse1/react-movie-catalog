# Deploy
- git init
- git add .
- git commit -m 'initial commit'
- git remote add origin <your repository link>
- git push origin master
- yarn deploy
- rm -rf node_modules/gh-pages/.cache
- git config --global credential.helper wincred



# Topics:
1. Hello World
2. Introducing JSX
3. Rendering Elements
4. Components and Props
5. State and Lifecycle
6. Handling Events
7. Conditional Rendering
8. Lists and Keys
9. Forms
10. Lifting State Up
11. Composition vs Inheritance
12. Thinking In React
13. Accessibility
14. Code-Splitting
  	- lazy loading of components in a page (except default one like error boundary)
	- lazy load routes components
	- reexport non named components for using lazy loading
15. Context
	- passing data from top most component to leaf label components
17. Error Boundaries
  	- capture error and show fallback view
18. Forwarding Refs
	- on click of button in parent, child function to be invoked ( access of child function through ref) 
19. Fragments
  	- grouping of childrent components without physical DOM
20. Higher-Order Components
	-   showing a loader, while a component waits for data
	-   Conditionally rendering components
	-   managing common user-interaction states
	-   providing components with specific styles
	-   and more generally, provide a component with just any prop that you want
	-   component composition ([https://codebrahma.com/using-higher-order-components-react-application/](https://codebrahma.com/using-higher-order-components-react-application/)) 
21. Integrating with Other Libraries
22. JSX In Depth
23. Optimizing Performance
24. Portals
  	- modal popup
25. Profiler
26. React Without ES6
27. React Without JSX
28. Reconciliation
29. Refs and the DOM
	- focus input on load of component which contains input control
30. Render Props
	https://softchris.github.io/pages/react-render-props.html#render-props-explained
31. Static Type Checking
32. Strict Mode
33. Typechecking With PropTypes
34. Uncontrolled Components
35. Web Components

https://medium.com/simply/comparison-hocs-vs-render-props-vs-hooks-55f9ffcd5dc6

