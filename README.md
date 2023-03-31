Repro of a stale ajs reference bug (the fix is turned on by default)

```sh
nvm use
npm i
npm start

# to repro bug, comment out from index.html
 if (window.analytics.initialized) {...}
```
click 'track' and observe console error.

PR: https://github.com/segmentio/snippet/pull/116/files
