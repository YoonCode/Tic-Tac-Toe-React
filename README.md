# Tic-Tac-Toe Tutorial

## [Final Result](https://codepen.io/gaearon/pen/gWWZgR?editors=0010)

## Declare Winner
1. props vs state
- how to pass props from parent to children component
- how to use state and setState for making components interactive

2. lifting state up
- how to maintain the value of each of the squares in one location(parent Board component)
- how to pass down a function from Board to Square, make Square call the function when a square is clicked

3. immutability
- how and why to create a copy of array and modify it, instead of modifying the existing array

4. function component 
- how and why to use function component instead of class component

5. taking turns and declaring a winner
- how to set conditional results
- stop when there's a winner

## Store History
1. lifting state up, again
- place history state in Game component(top-level)

2. showing past moves
- show all histories on Game component

3. picking a key
- how to differentiate each list item by using key to maintain state between re-renders