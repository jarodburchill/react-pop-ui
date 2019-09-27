# pop-ui

## Instalation

```
$ npm install react-pop-ui
```

## Components

### Navbar

#### Import

```javascript
import Navbar from "react-pop-ui";
```

#### Usage

```jsx
{
  /* Pass colors as Navbar attributes */
}
<Navbar bg="black" fg="white" hover="red">
  {/* A child with a 'brand=true' attribute will place 
    the element in the brand position on the navbar */}
  <a href="#home" brand="true">
    Website Brand
  </a>
  {/* All other children are treated as navbar links. 
    These links can be <a> tags or any variation of 
    the sort (i.e. <Link> tags from react-router) */}
  <a href="#home">Home</a>
  <a href="#projects">Projects</a>
  <a href="#blog">Blog</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</Navbar>;
```
