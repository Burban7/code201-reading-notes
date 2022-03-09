# ***More CSS Layout***


### ***Understanding the Display Property***

*************

- The **`Display`** property does two things:
  1. Determines if the applied box acts as inline or block.
  2. Determines how an element's children should behave.

- Elements such as **`<span>`** and **`<strong>`** are inline by default.

- You can't set a specific width/height on inline elements.

- Block elements create a new line for themselves and do not sit alongside eachother, as inoine elements do.

- The command **`display: flex`** makes the box a block-level box.


### ***Flexbox and Grid***

**********

- **Flexbox** is a mechanism used for one-dimensional layouts.
  - Will align the element's children next to eachother in the inline direction, and stretch them in the block direction by default.

```
.my-element {
  display: flex;
}
```

- Items will stay on the same axis and not wrap when they run out of space, but will try to squeeze onto the same line as eachother.

- Flexbox converts the child elements to be **flex items**, so you can write rules on how they will behave inside of a flex container.

- The **`flex`** property is a shorthand for **`flex-grow`** , **`flex-shrink`** and **`flex-basis`**.

- **Grid** is designed to control multi-axis layouts.

```
.my-element {
  display: grid;
}
```

- Enables you to write layour rules on any element that has **`display: grid`**

- Introduces new functions such as **`repeat()`** and **`minmax()`**

- The properties **`grid-row`** and **`grid-column`** instruct the first element in a grid to span to the start of the fourth column from the first, and span from the third row to the first.


