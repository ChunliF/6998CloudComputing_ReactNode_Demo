# 6998CloudComputing_Demo
ReactJS + NodeJS Demo for Spring 6998 Cloud Computing

A demonstration of basics in React and of linking the UI to a server backend

1. `cd` inside `demo_server` and run `npm install` to install server.js dependencies
2. `cd` inside `demo` and `npm install` again to install frontend dependencies
3. `npm start` inside the `demo` folder to run React front-end
4. `node server.js` in the root directory to run mock-up server code

## Calls to Backend
Pay attention to:
- the structure of the code
- the `render` method in each component and how it uses the rest of the component's functions
- how the `fetch` method (from the `whatwg-fetch` package) calls the server. This is a good way of calling the server in your own interfaces for your projects and homework assignments.
