# Use Onclickoutside hooks

Component Login use antd design

# Installing

Using npm

```ruby
$ npm install use-onclickoutside-hooks
import useOnClickOutside from 'use-onclickoutside-hooks'
```

Using yarn

```ruby
$ yarn add use-onclickoutside-hooks
import useOnClickOutside from 'login-components'
```

# Example

```ruby
import React, { useRef } from 'react';
import useOnClickOutside from 'use-onclickoutside-hooks'

export default function InputNumberCus({ items = [] }) {
  const ref = useRef();

  useOnClickOutside(ref, () => {
    ... use function
  });
  return (
    <div className="d-flex flex-row" ref={ref}>
      contet
    </div>
  );
}

```
