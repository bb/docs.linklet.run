# Quickstart

> This is an Beta release of Linklet.

## Before you begin

* Create a new [account](https://cloud.linklet.run/login) or login with your GitHub account
* Create a new service by pressing the plus sign and follow the instructions. This operation can take one minute.

## Create a function

* Create a new function by entering a function name. In this case __example__

__example__

```javascript
module.exports = (ctx, args, req, res) => {
  console.log('Example log output')
  ctx.success({
    msg: 'Example response'
  });
};
```
* Press the created function row and your can edit your Linklet function.


## Test the function

```bash
curl https://<your service name>.linklet.run/example
```
