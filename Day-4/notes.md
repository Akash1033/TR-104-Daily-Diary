
---

# Day 4 — useState Hook

`day4-state-usestate.md`

```markdown
# Day 4 – State and useState Hook

Today I learned about state in React.

State is used to store data that can change over time.

React provides a hook called `useState` to manage state inside functional components.

Example:

```jsx
import { useState } from "react";

function Counter() {

  const [count, setCount] = useState(0);

  return (
    <div>
      <h1>{count}</h1>
      <button onClick={() => setCount(count + 1)}>
        Increase
      </button>
    </div>
  );
}
