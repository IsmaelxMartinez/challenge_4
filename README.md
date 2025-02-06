# challenge_4

# Breaking UI into a component hierarchy
- Use the same technique as when you create a funciton or object, which is the single responsiblity rule,
one component should do one thing. If it ends up doing more then it could be broken down into subcomponents

# How is state and props are working in the application?
- Props are arguments you pass from the parent component that can be passed down to the child to change the appearance of it. Example of this is data from a api can be passed to a product card component that takes the data and shows it accordinly
- State is the data from a component. it keeps track of changes withiun the component, for example if you have api that returns a array of images, you can store that in state and it will change every time you search soemthing differently.