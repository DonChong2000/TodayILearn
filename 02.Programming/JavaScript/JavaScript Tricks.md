
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


# Convert NULL/Undefined to 0 using nullish coalescing
You can also use the nullish coalescing operator (??) to convert null or undefined to 0.

```js
let val = undefined;
val = val ?? 0;
console.log(val); // 👉️ 0
```
If the value to the left of the nullish coalescing operator (??) is equal to null or undefined, the value to the right is returned, otherwise, the value to the left of the operator is returned.

If the value to the left of the operator is not null or undefined, the variable gets assigned its current value.

```js
let val = 100;
val = val ?? 0;
console.log(val); // 👉️ 100
```
