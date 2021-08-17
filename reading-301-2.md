## React: Component Lifecycle events
This article by Joshua Blankenship can be found [here](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

Each component has several “lifecycle methods” that you can override to run code at particular times in the process. 

- Mounting: These methods are called in the following order when an instance of a component is being created and inserted into the DOM:

  * constructor
  * static getDerivedStateFromProps
  * render
  * componentDidMount
  * UNSAFE_componentWillMount (These methods are considered legacy and you should avoid them in new code)

- Updating: An update can be caused by changes to props or state. These methods are called in the following order when a component is being re-rendered: 
  * static getDerivedStateFromProps
  * shouldComponentUpdate
  * render
  * getSnapshotBeforeUpdate
  * componentDidUpdate
  * UNSAFE_componentWillUpdate
  * UNSAFE_componentWillReceiveProps

  - Unmounting: This method is called when a component is being removed from the DOM:
  * componentWillUnmount

  - Error Handling: These methods are called when there is an error during rendering, in a lifecycle method, or in the constructor of any child component.
  * static getDerivedStateFromError()
  * componentDidCatch()

## Video: React: State vs. Props
This video from Web Dev Simplified can be found [here](https://www.youtube.com/watch?v=IYvD9oBCuJI)

In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component.

## Additional Bookmarks:

- [React Bootstrap Documentation](https://react-bootstrap.github.io/)
- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
- [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)

[<---Back](README.md)