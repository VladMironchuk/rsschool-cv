# Vladislav Mironchuk

## Contact information
**Phone:** +375(33)327-80-41  
**Email:** vlad.mironchuk.02@gmail.com  
**Discord:** vladmiron01  
- - -

## Summary
My main goal is to become a Fullstack JS Developer. I am hardworking, responsible, very motivated.
- - -

## Skills
**Languages:** HTML, CSS, JS, SQL  
**Frameworks:** Node.js, Express.js  
**Technologies:** GIT, Docker, Swagger  
**Software:** Webstorm, Visual Studio Code, Figma 
- - -

## Code example
~~~
// Maximum subarray sum
function maxSequence(arr) {
  if(arr.length===0){return 0}
  let maxSum = 0;
  let partialSum = 0;

  for (let item of arr) { 
    partialSum += item; 
    maxSum = Math.max(maxSum, partialSum); 
    if (partialSum < 0) partialSum = 0; 
  }

  return maxSum;
}
~~~
- - -

## Courses 
1. [JavaScript Tutorial](https://learn.javascript.ru)
- - - 
