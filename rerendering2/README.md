## React & Re-rendering Vol.2

React elmemnts are immutable.

👉 Immutable means unchanging object.
We only need to pass elements through 'ReactDOM.render(element, rootElement);'
React takes care of the change judgment and reflection.

| Question                                | Answer                                                                 |
| --------------------------------------- | ---------------------------------------------------------------------- |
| What if the element type changes?       | Remove the previous element and draw a new one.                        |
| What if you have the same element type? | (Compare the keys first and) Compare the props to reflect the changes. |

📚REFERENCE : [reconcilation](https://ko.reactjs.org/docs/reconciliation.html)
