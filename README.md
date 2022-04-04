# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a library that can be used any UI layer or Framework.
It is mainly for use in React and for large apps. Redux helps make components more reusable.
```

2. What packages do we install to use Redux?

```
npm install react-redux redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
Redux makes it so none of the components store state so we can use it as props and pass it to any of the components.
```

4. What do we use in order to manage different pieces of state?

```
Reducers
```

5. What do we use to perform an update to state?

```
Actions
```

6. How do we access state from Redux?

```
Types
```

7. In your own words, describe how to set up Redux for a React App.

```
npm install react-redux redux
Create a store directory inside of the SRC folder with folders for Actions and Reducers, a types.js and index.js file.
In store/index.js:
  import { createStore } from 'redux'
In index.js in react import:
import {createRoot} from 'react-dom/client'
import { Provider } from 'react-redux'
import store from './store'
Then wrap the app component with the provider to give it access to the redux library/store:
    <React.StrictMode>
    <Provider store={store}>
      <App />
    </Provider>
  </React.StrictMode>
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
