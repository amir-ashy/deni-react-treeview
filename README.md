# deni-react-treeview-amir
A modern, themable and configurable treeview for React, Which support RTL


[site](https://denimar.github.io/deni-react-treeview/), [examples](https://denimar.github.io/deni-react-treeview/examples)


![alt text](https://denimar.github.io/deni-react-treeview/images/deni-react-treeview.png)


TODO: In the future I will implement the tests, Cloud CI.

## Installing with NPM

```
npm install deni-react-treeview-amir --save (React 16)
```

## Usage

Added to your react component
```html
    <TreeView url="https://denifakedata.herokuapp.com/tree/countries" rtl={true}/> 
```
For more details: [examples](https://denimar.github.io/deni-react-treeview/examples)

## API
[documentation](https://denimar.github.io/deni-react-treeview/api.html)

## Features
* Cross-Browser.
* Binding to a JSON (locally, remotely and lazy-load)
* Predefined Themes
* Theme Customization
* Events
* Checkboxes
* And so on...

## Properties
* autoLoad ```(boolean)```
* lazyLoad ```(boolean)```
* marginItems ```(integer)```
* selectRow ```(boolean)```
* showCheckbox ```(boolean)```
* showIcon ```(boolean)```
* showRoot ```(boolean)```
* theme ```(string)```
* rtl ```(boolean)```

## Events
* OnRenderItem
* onBeforeLoad
* onAfterLoad
* onSelectItem
* onExpanded
* onColapsed
* onLazyLoad
* onCheckItem

#### json example

```javascript
[
  {
    id: 100,
    text: 'Fruits',
    children: [
      {
        id: 101,
        text: 'Orange',
        isLeaf: true
      },
      {
        id: 102,
        text: 'Banana',
        isLeaf: true
      }
    ]
  },
  {
    id: 200,
    text: 'Vegetables',
    children: [
      {
        id: 201,
        text: 'Carrot',
        isLeaf: true
      },
      {
        id: 202,
        text: 'Tomato',
        isLeaf: true
      }
    ]
  }
]
```

## License

[MIT.](https://raw.githubusercontent.com/denimar/deni-react-treeview/master/LICENSE-MIT)

## Author

[Amirreza Sharifi](http://github.com/denimar) (sharifi.amirreza92@gmail.com) 
