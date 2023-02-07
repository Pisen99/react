# react notes 
React applications is nothing more than a collection of components composed together to create a user interface.
In react there's 2 main types of components.
stateless functional components - 
stateful class components - 

INSTALLATION
Terminal:
- npx create-react-app --use-npm (3 tools, it's node, npm & npx)
- cd my-app
- npm start

Note!
Everything I need will come with this installation. Anything I don't need I can delete later.

INSTALL (Chrome):
"React Developer Tools" then "add to chrome" (might need to re-open chrome after this).

Note!
When I'm on a site that uses react the icon will be lit up in either blue or orange.
Blue - site is running the production build of react (Optimized version)
Orange - Site is running the unoptimized develpment version.

Terminal:
- cd react-components/
- npm start

components (map)
- FunctionalGreeting.js (stateless functional components for components that are simple and don't need to change)
stateless functional greeting, basically a JavaScript function that returns HTML that you see in the browser preview.
A props.name is a jsx coming from "App.js" (line 9). 
- StatefulGreeting.js (stateful class components when you want your component to have some kind of interactivity)
- HooksCounter.js (Allow functional components to behave like stateful components with a lot less complexity)
Built in react function that can be added to a stateless functional component, this will allow it to behave like a stateful component

Which is best?
It depends.
Generally it's best to use functional componets as much as you can.
only use class componets when you need to have some sort of interactivity.

Lesson 3:
https://github.com/Code-Institute-Org/ci-react-core-react-components/generate