# reactify-elm

Reactify-Elm attempts to give an Elm App a React interface.

## Install
`npm i reactify-elm`

## Example
Running example [here](https://github.com/MoeSattler/reactify-elm/tree/master/example)
```
import reactify from 'reactify-elm'
import { UserContactElm } from './ElmApp'

const UserContactReact = reactify(UserContactElm)

const Wrapper = () => (
  <UserContactReact 
    name="John Johnson"
    email="John@jonson.com"
    onClick={() => console.log("BINGO!")}
  />
)
```
