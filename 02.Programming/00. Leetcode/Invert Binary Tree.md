# My solution without any input

### V1:
Code:
```js
var invertTree = function(root) {
    
    if(!root){return null}
    let temp = root.left;
    root.left = invertTree(root.right);
    root.right = invertTree(temp);
    return root;

};
```
Explaination:

simlpe recursion solution

# My solution with conceptual Input

### V1: 
Input:
Code:
```js

```
Explaination:

# My solution After studying others answer

### V1: 
Input:
```js

```
Code:
```js

```
Explaination: