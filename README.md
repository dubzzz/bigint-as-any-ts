# Polyfill bigint as any that works with TypeScript <3.2

If your project depends on a dependency declaring `bigint` in its typings you might have encountered the following error:

`Cannot find name 'bigint'`

In that case you should either bump to TypeScript >=3.2 or import this polyfill in your project.

In order to use it in your project, you have to import it in your code:

```typescript
import 'bigint-as-any-ts';
```