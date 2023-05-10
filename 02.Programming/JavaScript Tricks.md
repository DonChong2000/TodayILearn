
# Convert Boolean to 1 and 0 integer

```js
+(true) //= 1
+(false) //= 0
```

# Optional chaining operator
```js
const user = null;
console.log(user.name) // GG, error
console.log(user?.name); // undefined
```

This help you get values out of something that can be normal and null without error, and you can handle the null afterward.