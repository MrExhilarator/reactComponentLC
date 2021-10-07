# Component Life Cycle

- Mounting Phase
  - constructor()
  - render()
  - componentDidMount()
- Updating Phase
  - render()
- Unmounting phase
  - componentWillUnmount()
- Behind the scenes
  - Virtual DOM


There are 3 diff phases of component life cycle:
1.Mounting phase
2.Updating phase 
3.Unmounting phase

* In Mounting phase we mainly use 3 methods:
- constructor()		    
  - for setting up initial state and class variables
- render()		          
  - returning JSX that is displayed in the UI
- componentDidMount()	
  - operations on the components after initial render like setTimers, initiate API calls etc

all the methods are called in order

* In Updating phase:
when there is any change in the state object the render() method will be called

* In Unmounting phase, cleanup activities are performed like clearing timers and cancelling API calls etc, it has 1 method mainly:
- componentWillUnmount()
