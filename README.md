
# temp-react-lib

`temp-react-lib` is a lightweight library for building React components, written in TypeScript and bundled with Rollup. It includes a customizable Button component that can be easily integrated into your React applications.

## Installation

You can install `temp-react-lib` via npm or yarn:

```bash
npm install temp-react-lib --save
```
or

```bash
yarn add temp-react-lib
```
Usage
Button Component
The Button component allows you to create customizable buttons with various styles and behaviors. To use the Button component in your React application, import it as follows:
```bash
import React from 'react';
import { Button } from 'temp-react-lib';

const MyComponent = () => {
  return (
    <div>
      <Button onClick={() => console.log('Button clicked')}>Click me</Button>
    </div>
  );
};

export default MyComponent;
```
## Props
The Button component accepts the following props:

- `onClick`: Function called when the button is clicked.
- `disabled`: Boolean indicating whether the button is disabled.
- `className`: Additional CSS class names for custom styling.
- `style`: Inline styles to apply to the button.

```js
<Button onClick={() => console.log('Button clicked')} disabled={false} className="custom-button" style={{ color: 'red' }}>Click me</Button>
```
## Contributing
Contributions are welcome! If you'd like to contribute to temp-react-lib, please follow these steps:

- Fork the repository.
- Create your feature branch (git checkout -b feature/my-feature).
- Commit your changes (git commit -am 'Add my feature').
- Push to the branch (git push origin feature/my-feature).
- Submit a pull request.
## License
temp-react-lib is licensed under the MIT License. See LICENSE for more information.