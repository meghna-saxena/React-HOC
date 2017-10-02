# React Higher-Order Components

A higher-order component is a function that takes a component and returns a new component.
`const EnhancedComponent = higherOrderComponent(WrappedComponent);`

HOCs are common in third-party React libraries, such as Redux’s connect. 

Note: HOC doesn’t modify the input component, nor does it use inheritance to copy its behavior. Rather, an HOC composes the original component by wrapping it in a container component.

The wrapped component receives all the props of the container, along with a new prop, functionalities and data, which it uses to render its output. Thus, HOC makes an `"Enhanced" or "Composed" Component`.

[Reference](https://reactjs.org/docs/higher-order-components.html)

