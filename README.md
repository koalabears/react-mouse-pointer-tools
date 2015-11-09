# react-mouse-pointer-tools

Here's a link to the project on GitHub: https://github.com/koalabears/react-mouse-pointer-tools

react-mouse-pointer-tools is a react component that provides a toolkit for tracking the pointer position of the mouse. The toolkit provides both the x and y coordinates printed beside the pointer as well as optional horizontal and vertical rules for precision tracking. The colour of the lines and coordinates are customisable within the ReactDOM.render **_see the example use case below_**

![gif](https://cloud.githubusercontent.com/assets/12450298/10974076/3d789f12-83d8-11e5-9798-e4e2107a735d.gif)

## Example of how to use

``` javascript
var React         = require('react');
var ReactDOM      = require('react-dom');
var PointerTools  = require('react-mouse-pointer-tools');
var rootElement   = document.body.getElementById("wrapper");

ReactDOM.render(
  <PointerTools color="pink" showRulers={true} />,
  rootElement
);
```

| Prop  | Default  |Type | Description |
| :------------ |:---------------:| :-----------:| :---------------:|
| showRulers | true | boolean | displays/hides rulers|
| color | 'black' | string | changes the colour of rulers and coordinates |

### Why would you use it?

* Styling tool for web app layout
* User screen tracking
