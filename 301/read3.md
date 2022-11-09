# Class 3 Reading Notes

## Lists and Keys

1. Map() returns a new array

2. Example of how to loop through a list and display each in JSX

```const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```

3. Each list item needs a unique key

4. Keys help React identify which items have changed, are added, or are removed.

## Spread Operator

1. The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2. 4 things the spread operator can do: Copying an array, Concatenating or combining arrays, Using Math functions, Using an array as arguments

3. We render our application when we update our state

4. Example of combining an array:

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

5. Example of adding to an array:

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ] 
```

6. An example of using the spread operator to combine two objects into one:

``` const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## Pass Functions Between Componets

1. First thing a dev needs to do is to create the function wherever the state is that we want to change

2. The increment function loops through the poeple state and updates the count on a specific name

3. You pass a method from a parent component into a child component by referencing the method from the parent

4. The child component invokes a method that was passed to it from a parent component by calling it with props 

---

### Resources

[Lists & Keys](https://reactjs.org/docs/lists-and-keys.html)

[Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

[Pass Functions Between Componets](https://www.youtube.com/watch?v=c05OL7XbwXU)

---

[Back to Home](../README.md)
