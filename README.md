# App Using Global Context and useRef

- It uses Global Context in AppContext, from which provider is exported by default and the useGlobalContext custom hook is exported by name.
- useGlobalContext hook returns the GlobalContext which can be later used in other components.
- useRef hook refers to name input in AddUser, and on load it focuses that element to make it more usable.

# Custom Hook
- This app uses custom Hook useGlobalContext() hook which returns the globalContext.
- We can call this hook anywhere further down the component tree to use props passed down to provider component in that child component.

# Live App
https://global-context-useref.netlify.app/
