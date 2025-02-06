---
stoplight-id: zp36of11obhc7
---

# article1 - github

The beginning of an awesome article...

More content added 


# Code Blocks

<!-- 
title: This is Javascript
lineNumbers: true
-->
```javascript
function fibonacci(num) {
  var a = 1,
    b = 0,
    temp;

  while (num >= 0) {
    temp = a;
    a = a + b;
    b = temp;
    num--;
  }

  return b;
}
```

```json title="This is JSON" lineNumbers
{
  "foo": "bar"
}
```
