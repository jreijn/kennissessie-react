### Building modern web applications with React - Luminis

##### Goals
In this workshop we want you to get familiar with React. We try to incorporate things like using props, state and creating a component to show how React works. 
This is the beginning of React, feel free to try more than what we have prepared!

##### Getting started
- Run `npm install` from the root of this project
- Run `npm start` to start the application
- Navigate to `localhost:3000` to see the App
- Run `npm test` to start Jest. The first assignments are done when all tests succeed

##### Assignments

###### Speaker
In the first 6 assignments we are going to fill the speakers page. 
We need to use `ListHeaders`, similar as in the schedule page. We need to use and modify the `Speaker` component too. 
After these assignments the `/speakers` page should show speakers grouped by the first letter of their name. When you click on the speaker you should be able to see the details 

1. In `speakers.js`, add a `ListHeader` per group
    - The `ListHeader` is a common component which can be found `/common/list-header.js`. The import is already done in `speakers.js`
2. In `speakers.js`, add a `Speaker` per speaker in the group
    - The `Speaker` is a component which can be found in `/speakers/speaker.js`. The import is already done in `speakers.js`
3. In `speakers.js`, add a speaker as a prop of `Speaker`
    - To add props to a component see `https://reactjs.org/docs/components-and-props.html`
4. In `speaker.js`, show the speaker name 
    - Using the added speaker prop, show the name of the speaker in `speaker.js`
5. In `speaker.js`, use a click event to show and hide a detail view where you can see speaker details
    - To add a click event in a component see `https://reactjs.org/docs/handling-events.html`
6. In `speaker.test.js`, try to test the `Speaker` component
    - The `speakers.test.js` already contains some tests, you can take this as a starting point. Otherwise see `https://jestjs.io/` and `http://airbnb.io/enzyme/`

###### About
In the last 4 assignments we are going to make a new page with a route.
We need to create a component, update the routes in `app.js` and do anything you like for the about page

1. In the folder about, create an `About` component
    - We now only have a `tmp.txt` to show the about folder. Remove this and add `about.js` with the `About` component 
2. In `app.js`, create a new route to `/about`
    - Create a link similar to those of `/schedule`
3. In `app.js`, use `About`
    - Each route needs a component to render. Use `About` in the same way as we did in the other routes
4. In `about.js`, use the data from `data/conference-data.js` to create something you like

##### Links
- React: `https://reactjs.org/`
- Create React App - Quickly setup a project: `https://github.com/facebook/create-react-app`
- React router: `https://reacttraining.com/react-router/`
- Jest - Testing framework: `https://facebook.github.io/jest`
- Enzyme - Mounting components for testing: `http://airbnb.io/enzyme/`
