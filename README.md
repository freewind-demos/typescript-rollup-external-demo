TypeScript Rollup External Demo
===============================

注意，external中的值必须是import进来的完整的值。

比如，对于

```
import capitalize from 'lodash/capitalize';
```

external中应该写`external: ['lodash/capitalize']`，而不是`external: ['lodash']`，否则无效。

这里需要特别注意

```
npm install
npm run demo
```
