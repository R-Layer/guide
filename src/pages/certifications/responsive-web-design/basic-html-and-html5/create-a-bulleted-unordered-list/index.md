---
title: Create a Bulleted Unordered List
---
## Create a Bulleted Unordered List

To pass the challenge the first operation you should do is to remove the `p` elements with all their content.

After that you have to implement the list: to create it in the right way the `ul` tag should have no content but the `li`'s. 
It means that every text inside the `ul` has to be between the opening tag ( `<li>` ) and the closing tag (`</li>`) of any `li` element.

Correct: 
```
<ul>
  <li>Some text</li>
</ul>
```
Not correct: 
```
<ul>
  <li>Some text</li>
  Some loose text
</ul>
```

Finally, you need to put at least three `li` element inside the `ul` element and these `li` must be on the same level, not nested into each other:

Correct: 
```
<ul>
  <li></li>
  <li></li>
</ul>
```
Not correct: 
```
<ul>
  <li>
    <li>
    </li>
  </li>
</ul>
```

Good luck!
