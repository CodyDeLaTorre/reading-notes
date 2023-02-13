# Class 39 Reading Notes

## REACT Review 3

### NextJS

- Next JS development server has a fast refresh so when you make a change you see it almost instantaneously
- us Link component to link all of your pages
- use Link over a tags because it allows you to do client-side navigation and accepts props.
- use Image over img tags: your build times aren't increased, whether shipping 10 images or 10 million images. Images are lazy loaded by default. That means your page speed isn't penalized for images outside the viewport. Images load as they are scrolled into viewport.
- Use Head instead of the head tag
- Next js supports a wide variety of CSS: modules, sass, Tailwind, JS css

### React Context

An easier state

- allows us to pass and use data in whatever component w/out using props
There are four steps to using React context:

- Create context using the createContext method.
- Take your created context and wrap the context provider around your component tree.
- Put any value you like on your context provider using the value prop.
- Read that value within any component by using the context consumer.

#### What I want to know more about

- Doesnt tell us why to use Head over head

---

### Resources

[Next JS](https://nextjs.org/learn/basics/create-nextjs-app)

[React Context](https://www.freecodecamp.org/news/react-context-for-beginners/#what-is-react-context)

---

[Back to Home](../README.md)
