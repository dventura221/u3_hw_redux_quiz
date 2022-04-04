# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux allows React to store state, so that state and its changes can be used anywhere, bypassing the need to pass state through props, such as with vanilla React.
```

2. What packages do we install to use Redux?

```
npm install react-redux redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
User interacts with UI, triggers an event/dispatch causing an Action to update state in the Store. A reducer manages a portion of that state, then once the specfic state has been updated, the UI is also updated to reflect any changes.
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
Map State to Props, then Map Action to Props, then connect component to Redux, to finally access state/Store.
```

7. In your own words, describe how to set up Redux for a React App.

```
Install Redux to your app. Create a store folder in the src folder with an index.js. Set-up Provider in your index.js around your App. Set-up Reducers and initial state in the store folder. To set-up actions, create a type.js in the store folder, and create an actions folder in the store folder, and within create a .js file to write your actions. Next, will need to map state and actions to props, connect to the componenet, in order for the store state to be accessed by the React app/components.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
