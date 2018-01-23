# React Advanced Form Addons
A collection of tools for fast form prototyping using [React Advanced Form](https://github.com/kettanaito/react-advanced-form).

## Getting started

### Install
#### NPM:
```bash
npm install react-advanced-form-addons --save
```

#### Yarn:
```bash
npm install react-advanced-form-addons
```

> **Note:** You would need to have `react-advanced-form` installed as a peer dependency in order to use this prototyping tool.

### Prototype!
```jsx
import React from 'react';
import { Form } from 'react-advanced-form';
import { Input, Select } from 'react-advanced-form-addons';

export default class FormPrototype extends React.Component {
  render() {
    return (
      <Form action={ ... }>
        <Input name="username" required />
        <Select name="role" required>
          <option value="admin">Administrator</option>
          <option value="editor">Content editor</option>
        </Select>
      </Form>
    );
  }
}
```

## License
This project is issued under [MIT License](./LICENSE).

