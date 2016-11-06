# reactify-elm

Reactify-Elm attempts to give an Elm App a React interface.

## Example
Running example [here](https://github.com/MoeSattler/reactify-elm/tree/master/example)
```
import reactify from 'reactify-elm'
import { ElmApp } from './ElmApp'

const ReactComponent = reactify(ElmApp)

const Wrapper = () => (
  <ReactComponent value="CLICK ME!" onClick={() => console.log("BINGO!")}/>
)
```
