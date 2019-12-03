React Native Metro-Bundle
===

#### \node_modules\metro-config\src\defaults\blacklist.js
---

```gherkin=
var sharedBlacklist = [
  /node_modules[/\\]react[/\\]dist[/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
```
> Change to:


```gherkin=
var sharedBlacklist = [
  /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
```

> Read more:
> https://stackoverflow.com/questions/58120990/how-to-resolve-the-error-on-react-native-start/58199866#58199866
> https://stackoverflow.com/questions/58120990/how-to-resolve-the-error-on-react-native-start
