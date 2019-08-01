# 📝 VS Code React snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/runningcoder.react-snippets.svg)](https://vsmarketplacebadge.apphb.com/version/runningcoder.react-snippets.svg)

This extension provides you React/Redux snippets for [VS Code](https://code.visualstudio.com/)

## 📚 Supported languages (file extensions)

* JavaScript (.js)
* JavaScript React (.jsx)
* TypeScript (.ts)
* TypeScript React (.tsx)

## 📖 Snippets

Below is a list of all available snippets and the triggers of each one. The `⇥` means the `TAB` key.

### React Component

#### Lifecycle

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>rcns⇥</code></td>
  <td>   

```jsx
constructor(props) {
  super(props)

  this.state = {
    
  }
}
```

  </td>
  <td>   

```tsx
constructor(props: Props) {
  super(props)

  this.state = {
    
  }
}
```

  </td>
</tr>

<tr>
  <td><code>cdm⇥</code></td>
  <td>   

```jsx
componentDidMount() {

}
```

  </td>
  <td>   

```tsx
componentDidMount(): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cdu⇥</code></td>
  <td>   

```jsx
componentDidUpdate(prevProps, prevState, snapshot) {

}
```

  </td>
  <td>   

```tsx
componentDidUpdate(prevProps: Props, prevState: State, snapshot: any): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cdc⇥</code></td>
  <td>   

```jsx
componentDidCatch(error, info) {

}
```

  </td>
  <td>   

```tsx
componentDidCatch(error: Error, info: ErrorInfo): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cwu⇥</code></td>
  <td>   

```jsx
componentWillUnmount() {

}
```

  </td>
    <td>   

```tsx
componentWillUnmount(): void {

}
```

  </td>
</tr>

<tr>
  <td><code>scu⇥</code></td>
  <td>   

```jsx
shouldComponentUpdate(nextProps, nextState) {

}
```

  </td>
  <td>   

```tsx
shouldComponentUpdate(nextProps: Props, nextState: State): boolean {

}
```

  </td>
</tr>

<tr>
  <td><code>gdsfp⇥</code></td>
  <td>   

```jsx
static getDerivedStateFromProps(nextProps, prevState){

}
```

  </td>
  <td>   

```tsx
static getDerivedStateFromProps(nextProps: Readonly<Props>, prevState: State): Partial<State> | null {

}
```

  </td>
</tr>

<tr>
  <td><code>gdsfe⇥</code></td>
  <td>   

```jsx
static getDerivedStateFromError(error){

}
```

  </td>
  <td>   

```tsx
static getDerivedStateFromError(error: any): Partial<State> | null {

}
```

  </td>
</tr>

<tr>
  <td><code>gsbu⇥</code></td>
  <td>   

```jsx
getSnapshotBeforeUpdate(prevProps, prevState){

}
```

  </td>
  <td>   

```tsx
getSnapshotBeforeUpdate(prevProps: Readonly<Props>, prevState: Readonly<State>): SnapShot | null {

}
```

  </td>
</tr>

<tr>
  <td><code>ren⇥</code></td>
  <td>   

```jsx
render(){

}
```

  </td>
  <td>   

```tsx
render(): React.ReactNode {

}
```

  </td>
</tr>


</tbody>
</table>



#### Class Properties

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>cdp⇥</code></td>
  <td>   

```jsx
Component.defaultProps = {
  
}
```

  </td>
  <td>   

```tsx
Component.defaultProps = {
  
}
```

  </td>
</tr>
</tbody>
</table>

#### Instance Properties

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>thp⇥</code></td>
  <td>   

```jsx
this.props.
```

  </td>
  <td>   

```tsx
this.props.
```

  </td>
</tr>
<tr>
  <td><code>ths⇥</code></td>
  <td>   

```jsx
this.state.
```

  </td>
  <td>   

```tsx
this.state.
```

  </td>
</tr>
</tbody>
</table>

#### Refs

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>cref⇥</code></td>
  <td>   

```jsx
this.nameRef = React.createRef()
```

  </td>
  <td>   

```tsx
this.nameRef = React.createRef<Type>()  
```

  </td>
</tr>
<tr>
  <td><code>fcref⇥</code></td>
  <td>   

```jsx
const nameRef = React.createRef()
```

  </td>
  <td>   

```tsx
const nameRef = React.createRef<Type>()
```

  </td>
</tr>
</tbody>
</table>

#### Context

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>cct⇥</code></td>
  <td>   

```jsx
const contextName = React.createContext(defaultValue)
```

  </td>
  <td>   

```tsx
const contextName = React.createContext<Type>(defaultValue)
```

  </td>
</tr>
<tr>
  <td><code>ctp⇥</code></td>
  <td>   

```jsx
<Context.Provider value="value">
  
</Context.Provider>
```

  </td>
  <td>   

```tsx
<Context.Provider value="value">
  
</Context.Provider>
```

  </td>
</tr>
<tr>
  <td><code>ctc⇥</code></td>
  <td>   

```jsx
<Context.Consumer>
  {value => ()}
</Context.Consumer>
```

  </td>
  <td>   

```tsx
<Context.Consumer>
  {value => ()}
</Context.Consumer>
```

  </td>
</tr>
</tbody>
</table>


#### Others

<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>ss⇥</code></td>
  <td>   

```jsx
this.setState({})
```

  </td>
  <td>   

```tsx
this.setState({})
```

  </td>
</tr>

<tr>
  <td><code>ssu⇥</code></td>
  <td>   

```jsx
this.setState((state, props) => {
  return {stateChange}
})
```

  </td>
  <td>   

```tsx
this.setState((state, props) => {
  return {stateChange}
})
```

  </td>
</tr>

</tbody>
</table>


### Skeleton

#### `rcc⇥`

##### JS

```jsx
import React, { |PureComponent,Component| } from 'react'

class FileName extends |PureComponent,Component| {
  constructor(props) {
    super(props)

    this.state = {
      
    }
  }

  render() {
    return (
      
    )
  }
}

export default FileName

```

##### TS

```tsx
import React, { |PureComponent,Component|, ReactNode } from 'react'

interface Props {}
interface State {}

class FileName extends |PureComponent,Component|<Props, State> {
  constructor(props: Props) {
    super(props)

    this.state = {
      
    }
  }

  render(): ReactNode {
    return (
      
    )
  }
}

export default FileName

```

#### `rccp⇥`

##### JS

```jsx
import React, { |PureComponent,Component| } from 'react'
import PropTypes from 'prop-types'

class FileName extends |PureComponent,Component| {
  constructor(props) {
    super(props)

    this.state = {

    }
  }

  render() {
    return (

    )
  }
}

export default FileName

```

#### `rfc⇥`

##### JS

```jsx
import React from 'react'

function FileName() {
  return (

  )
}

export default FileName

```

##### TS

```tsx
import React from 'react'

interface Props {}

function FileName(props: Props) {
  const {} = props

  return (
    
  )
}

export default FileName

```

#### `rfcp⇥`

##### JS

```jsx
import React from 'react'
import PropTypes from 'prop-types'

function FileName(props) {
  const {} = props

  return (

  )
}

FileName.propTypes = {

}

export default FileName

```

#### `rfmc⇥`

##### JS

```jsx
import React, { memo } from 'react'

function FileName() {
  return (
    
  )
}

export default memo(FileName)

```

##### TS

```tsx
import React, { memo } from 'react'

interface Props {}

function FileName(props: Props) {
  const {} = props

  return (
    
  )
}

export default memo(FileName)

```

#### `rfmcp⇥`

##### JS

```jsx
import React, { memo } from 'react'
import PropTypes from 'prop-types'

function FileName(props) {
  const {} = props

  return (
    
  )
}

FileName.propTypes = {}

export default memo(FileName)

```

#### `rccrdx⇥`

##### JS

```jsx
import React, { PureComponent } from 'react'
import { connect } from 'react-redux'

class FileName extends PureComponent {
  constructor(props) {
    super(props)

    this.state = {

    }
  }

  render() {
    return (

    )
  }
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

##### TS

```tsx
import React, { |PureComponent,Component| } from 'react'
import { connect } from 'react-redux'

interface Props {}
interface State {}

class FileName extends |PureComponent,Component|<Props, State> {
  constructor(props) {
    super(props)

    this.state = {
      
    }
  }

  render() {
    return (
      
    )
  }
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

#### `rccprdx⇥`

##### JS

```jsx
import React, { PureComponent } from 'react'
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

class FileName extends PureComponent {
  static propTypes = {

  }

  constructor(props) {
    super(props)

    this.state = {

    }
  }

  render() {
    return (

    )
  }
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

#### `rfcrdx⇥`

##### JS

```jsx
import React from 'react'
import { connect } from 'react-redux'

function FileName() {
  return (

  )
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

##### TS

```tsx
import React from 'react'
import { connect } from 'react-redux'

interface Props {}

function FileName(props: Props) {
  const {} = props

  return (

  )
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

#### `rfcprdx⇥`

##### JS

```jsx
import React from 'react'
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

function FileName(props) {
  const {} = props

  return (

  )
}

FileName.propTypes = {
  
}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(FileName)

```

#### `rfmcrdx⇥`

##### JS

```jsx
import React, { memo } from 'react'
import { connect } from 'react-redux'
import PropTypes from 'prop-types'

function FileName() {
  return (

  )
}

FileName.propTypes = {

}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(memo(FileName))

```

##### TS

```tsx
import React, { memo } from 'react'
import { connect } from 'react-redux'

interface Props {}

function FileName(props: Props) {
  const {} = props

  return (

  )
}

FileName.propTypes = {

}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(memo(FileName))

```

#### `rfmcprdx⇥`

##### JS

```jsx
import React, { memo } from 'react'
import { connect } from 'react-redux'
import PropTypes from 'prop-types'

function FileName(props) {
  const {} = props

  return (

  )
}

FileName.propTypes = {}

const mapStateToProps = (state) => ({
  
})

const mapDispatchToProps = (dispatch) => ({
  
})

export default connect(mapStateToProps, mapDispatchToProps)(memo(FileName))

```
