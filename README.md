# rfs-js-import-composition

More terse import statements grouped for a base directory.

```js
import {
  { Foo } from './foo',
  Bar from './extra/bar'
} from '../../components'
```

equivalent to:

```js
import { Foo } from '../../components/foo'
import Bar from '../../components/extra/bar'
```
