Options are passed to the `init()` as object:

```javascript
import * as Sentry from '@sentry/browser';

Sentry.init({
  environment: '{{ page.example_environment }}',
})
```
