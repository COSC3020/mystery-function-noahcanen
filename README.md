# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

This function returns the largest item in the array. 

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```
For this assignment, I was able to do it entirely on my own with a little help looking up syntax from the Internet.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
