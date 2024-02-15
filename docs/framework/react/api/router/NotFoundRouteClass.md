---
id: NotFoundRouteClass
title: NotFoundRoute class
---

## ⚠️ Deprecated

The `NotFoundRoute` API has been deprecated in favor of the `notFoundComponent` route option. See the [not found errors guide](./guide/not-found-errors) for more information.

The `NotFoundRoute` class extends the `Route` class and can be used to create a not found route instance. A not found route instance can be passed to the `routerOptions.notFoundRoute` option to configure a default not-found/404 route for every branch of the route tree.

### `NotFoundRoute` constructor

#### `options`

```tsx
Omit<
  RouteOptions,
  | 'path'
  | 'id'
  | 'getParentRoute'
  | 'caseSensitive'
  | 'parseParams'
  | 'stringifyParams'
>
```

- Required
- The options that will be used to configure the not found route instance
