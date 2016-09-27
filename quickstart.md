# Quickstart

> This is an Beta release of Linklet.

## Before you begin

## Create a function

__example__

```javascript
module.exports = (ctx, args, req, res) => {
  // console.log('Example log output')
  ctx.success({
    // msg: 'Example response'
  });
};
```

## Test the function

```bash
curl https://<your service name>.linklet.run/example
```

## View logs
