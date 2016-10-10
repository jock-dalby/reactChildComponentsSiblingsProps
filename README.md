# reactChildComponentsSiblingsProps

React programming pattern:

1. A stateful, parent component passes down a prop to a stateless, child component.

2. No.1's pattern is actually part of a larger pattern: a stateful, parent component passes down an event handler to a stateless, child component. The child component then uses that event handler to update its parent's state.

3. A child component updates its parent's state, and the parent passes that state to a sibling component.

Child components have two jobs:

1 - Child components display a name.

2 - Child components offer a way to change that name.

You should divide Child components in two: one component for displaying the name, and a different component for allowing a user to change the name.

You will have one stateless component display information, and a different stateless component offer the ability to change that information.
