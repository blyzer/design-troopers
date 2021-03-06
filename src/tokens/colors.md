### Usage

```js
import { InlineCode } from '../docs/doc_components';

<div>
  <div className="dt-text-primary">
    <p className="dt-pl-2"><InlineCode text=".dt-text-primary" /> to change text color to primary</p>
  </div>
  <div className="dt-bg-gray-900 dt-my-6">
    <p className="dt-py-4 dt-pl-2 dt-text-white"><InlineCode text=".dt-bg-gray-900" /> to make background color to dark gray shade</p>
  </div>

  <h5><InlineCode text=".dt-text-primary" /> is same as <InlineCode text=".dt-text-primary-500" /></h5>
</div>
```

### Colors Chart

Click on the color name to copy the name like `primary-300`. If you click the name while holding `Option` key it will copy the class name like `.dt-primary-300`.

```js
import { ColorChart } from '../docs/doc_components';
const tokens = require('./tokens.js');

const { colors } = tokens;

<ColorChart colors={colors} />
```
