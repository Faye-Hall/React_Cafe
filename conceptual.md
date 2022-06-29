### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
- > To handle mapping between URL bar and page user sees via browser rather than via server.

- What is a single page application?
- > An application that does not load new pages from the server.

- What are some differences between client side and server side routing?
- > Client-side the processing takes place on the user's computer.

- What are two ways of handling redirects with React Router? When would you use each?
- > Using the Redirect component & Using the history object. Use Redirct for 404 responses and history for page navigation.

- What are two different ways to handle page-not-found user experiences using React Router?
- > using the Redirect component and the Switch component.

- How do you grab URL parameters from within a component using React Router?
- > With the useParams hook that you can import from react-router-dom.

- What is context in React? When would you use it?
- > Context is a way to pass data or functions across different components in a hierarchy without needing to use props.

- Describe some differences between class-based components and function
  components in React.

  > Class-based components use OOP to manage state, props, and the lifecycle of a component. Because they are based on OOP, you'll see the this keyword used extensively. You also need to be sure to bind any instance methods in the constructor, so that you don't lose the this context. There are several methods used to hook into the component lifecycle, including componentDidMount, componentDidUpdate, and componentWillUnmount. In contrast, function components do not use OOP, instead favoring hooks to manage state and the component lifecycle. You don't need to reference this or worry about method binding, and one hook (useEffect) replaces the need for the lifecycle methods mentioned above.

- What are some of the problems that hooks were designed to solve?

> One of the benefits of using hooks is the ability to write custom hooks that can be shared across components. This has the benefit of keeping our code DRY; instead of having common business logic duplicated across several components, we can keep that logic in a single custom hook that is then shared. There's also less boilerplate required to make a component stateful (we don't have to use the keyword this or method bind in the constructor).
