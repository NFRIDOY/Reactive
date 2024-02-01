# Reactive
## Core React 
## useReducer
```
const initalState = 0;
const reducer = (state, action) => {

}

function App() {
  const [count, setCount] = useState(0)
  // here state is new state. 
  const [state, dispatch] = useReducer(reducer, initalState);
}
```
