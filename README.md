# Reactjs-popup without inline-css for modals

[Reactjs-popup](https://github.com/yjose/reactjs-popup) is a simple react popup component.

Removed the css styling for modals to add own styling later

## Installing

```bash
npm i paolomolo/reactjs-popup-lib#master -S
```

Requires React >= 16.0  

## Include the Component

To start using reactjs popup you just need to import the component from the reactjs-popup package.

```jsx
import React from "react";
import Popup from "reactjs-popup";

export default () => (
  <Popup trigger={<button> Trigger</button>} position="right center" modal>
    <div>Modal content here</div>
  </Popup>
);
```

You can find more examples in the [reactjs-popup home page](https://react-popup.netlify.com)
