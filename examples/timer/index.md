## A Dynamic Component

A component in vomit is a term used to describe a function that takes data and returns a DOM element.

```vomit
function component(name) {
  return vomit`<div>Hello ${name}</div>`
}
```