---
title: Remove an Item from an Array
---
## Remove an Item from an Array

To remove an item from the array, we can the use [filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) method to take out the item with that particular index.

```
return state.filter((item,index) => index !== action.index)
```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
