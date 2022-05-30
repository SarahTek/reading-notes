# Passing Functions as props


1. What does .map() return?

Unlike forEach() , It returns It returns a new array and elements of arrays are result of callback function.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

I can attach map() method to the array and pass a callback function that gets called for each iteration. 

3. Each list item needs a unique IDs.

4. What is the purpose of a key?

Key helps React identify which item has been added , changed or removed.



1. What is the spread operator?
- Spread syntax(...) allows the iterable object array to expand in to a list of argument. 
2. List 4 things that the spread operator can do.
- copying an array
- Concatenating or combining arrays
- adding an item to list
- combining object
- Converting NodeList to an array
- Using Math functions
- Using an array as arguments

3. Give an example of using the spread operator to combine two arrays.
```
 const create = [ 1,2,3,4]
  const numbers =  [ 5,6,7,8] 
  const createnumbers = {...create,...numbers}
  console.log(createnumbers)
```



4. Give an example of using the spread operator to add a new item to an array.
```
const favFoods = [ pizza, lasagna , shiro];
const moreFoods = [...favFoods];
favFoods[0] = 'chickenparm'
console.log(...[favFoods,'...',moreFoods])
```
5. Give an example of using the spread operator to combine two objects into one.
```
const oldArray = [ pink,green,yellow];
const newArray = [ purple, red,blue];
  const myArry = [ ...oldArray,...newArray];
  console.log(...myArray)
```



1. In the video, what is the first step that the developer does to pass functions between components?
- he created an arrow function that loops over the people array using map() and it increments the each time and returns an updated new array. 
2. In your own words, what does the increment function do?
- it is increamenting the count that was passed to the object each time the user clicks to the people array and retuns a new array.
3. How can you pass a method from a parent component into a child component?
- we can pass a method from parent to child by using props. we can access the data by usinf `(this.props)`
4. How does the child component invoke a method that was passed to it from a parent component?
- The child component invokes the parent callback function using `props`.



### Resorces
- [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

- [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
- [How to pass functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
- 
