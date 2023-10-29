> [I got banned from linked in for writing JS 😆 - YouTube](https://www.youtube.com/watch?v=zU-QcfOrvCk&ab_channel=WesBos)




# Test

Task: Check all [Grind 75](https://www.techinterviewhandbook.org/grind75)boxes

![](../../z.Images/Pasted%20image%2020230601164203.png)

Using `$$('[aria-label*="as complete"]')` We selected all buttons

![](../../z.Images/Pasted%20image%2020230601164327.png)

Now only the First Element will click. idky,

But I force it by this anyway, and it click all the button
```
const button = $$('[aria-label*="as incomplete"]');
for(let i=0;i<button.length;i++){
   $$('[aria-label*="as incomplete"]').forEach(e=>e.click())
}
```