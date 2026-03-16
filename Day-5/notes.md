
---

# Day 5 — Events in React

`day5-events.md`

```markdown
# Day 5 – Event Handling in React

Today I learned how event handling works in React.

Events are used to respond to user actions like clicking a button, typing in an input field, or submitting a form.

Example:

```jsx
function App() {

  function handleClick() {
    alert("Button clicked");
  }

  return (
    <button onClick={handleClick}>
      Click Me
    </button>
  );
}
