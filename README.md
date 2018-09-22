## A react app: Memory Game

Instruction:
- Click on the card to flip the color.
- If the 2 cards color do not match, they will flip back after 1.3 seconds. Note during this 1.3 seconds you won't be able to flip color on any other cards. 
- If the 2 color match, then they will stay.
- Click the New Game on the Navbar to restart the game.

Tech Stack Used in React:
- props, prop-types, state, setState
- functional / stateless components

Pay Attention to:
- JS Ojbects defined outside component
- bind functions in component state
- pass functions to stateless component through props
- function in function: handleClick > mapCardState
- setState({cards, noClick}) can add new state noClick