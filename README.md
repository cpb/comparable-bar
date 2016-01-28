# comparable-bar
A VictoryJS component for stacked bar charts that lets users hover and click to compare the values encoded in a bar.

## Get started

1. Add Victory to your project:
  ```
  npm install comparable-bar --save
  ```
2. Add your first Victory component:

  ```jsx
  import React, { Component } from 'react';
  import { render } from 'react-dom';
  import ComparableBar from 'comparable-bar';

  class MyLovelyBarChart extends Component {
    render() {
      return (
        <ComparableBar />
      );
    }
  }

  render(<MyLovelyBarChart />, document.getElementById('app'));
  ```
3. `ComparableBar` component will be rendered, and you should see:
![Default Rendering of ComparableBar](https://raw.githubusercontent.com/cpb/comparable-bar/master/docs/sample.png)
