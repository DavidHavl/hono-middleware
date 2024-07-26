# @hono/event-emitter

## 2.0.0

### Major Changes

- [`ec5e61d9b0ee4a3764821ba31fb0f42b314b5908`](https://github.com/honojs/middleware/commit/ec5e61d9b0ee4a3764821ba31fb0f42b314b5908) Thanks [@DavidHavl](https://github.com/DavidHavl)! - ### Added:

  - New `emitAsync` method to the EventEmitter to enable invoking asynchronous handlers.
  - Added prevention for potential memory leak when adding handlers inside of middleware via `on` method.
  - Introduced new option of EventEmitter `maxHandlers` that limits number of handlers that can be added to a single event.
  - Significantly improved documentation.

  ### Changed:

  - Moved context parameter to the first position in the `emit` method.

## 1.0.0

### Major Changes

- [#615](https://github.com/honojs/middleware/pull/615) [`53b4f331906f3da57da81e87d461889d0aff5cb4`](https://github.com/honojs/middleware/commit/53b4f331906f3da57da81e87d461889d0aff5cb4) Thanks [@DavidHavl](https://github.com/DavidHavl)! - Full release of Event Emitter middleware for Hono
