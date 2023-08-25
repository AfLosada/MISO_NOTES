Transitions trigger switches between [[state]]s, activating or inactivating them.
## trigger
A trigger can be anything that activates a transition between states. It is mostly input from an external user, but triggers can also be tied to [[internal behavior]] of the state.
They are written in UML like this: `trigger[guard] / behavior`
Ex: `keystroke [input = required_length] / submit input`
![[Pasted image 20230824221418.png]]

## guard
It is the condition for the activation of a transition given a trigger. If the guard is not passed, then the transition may not activate the other state, it may not activate the behavior.

### behavior
What will happen when the trigger passes the guard

You can also model guards and triggers as [[signals]].

