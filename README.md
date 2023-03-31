A repo for reproducing a stale reference bug (the fix is turned on by default)

```sh
nvm use
npm i
npm start

# to repro bug, comment out from index.html
 if (window.analytics.initialized) {...}

# click 'track' and observe console.
```
