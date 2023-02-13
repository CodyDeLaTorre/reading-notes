# Class 38 Reading Notes

## REACT Review 2

### REACT

- You can reder html elemts or whole pages conditionally by using if statements. Normally used for authentication purposes.

ex

```JavaScript
function Greeting(props) {
  const isLoggedIn = props.isLoggedIn;
  if (isLoggedIn) {
    return <UserGreeting />;
  }
  return <GuestGreeting />;
}
```

const root = ReactDOM.createRoot(document.getElementById('root')); 
// Try changing to isLoggedIn={true}:
root.render(<Greeting isLoggedIn={false} />);

- You can use lists to render multiple components by mapping or using for each methods and creating elements for each item.
- You can easily render Forms as well with Reac just like any other HTML element. You have to make functions to handle the submits though and make sure to preventDefault!!!

---

### Resources

[REACT Overview](https://reactjs.org/docs/hello-world.html)

---

[Back to Home](../README.md)
