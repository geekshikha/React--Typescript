# Creating a TODO List by using React with Typescript!


## Using - Generic Type

Generics offer a way to create reusable components. Generics make components work with any data type. Components can be used with a variety of data types.

In below code snippet, `TodoItem` function takes `props` and using Generic Type we specified type of `text` and `onRemoveTodo` function.

```javascript
const TodoItem: React.FC<{ text: string; onRemoveTodo: () => void }> = (
  props
) => {
  return (
    <li className={classes.item} onClick={props.onRemoveTodo}>
      {props.text}
    </li>
  );
};

export default TodoItem;
```

### Adding Slides

<img width="764" alt="Screenshot 2022-03-08 at 14 11 33" src="https://user-images.githubusercontent.com/79321645/157244801-66f06c33-8cf9-462d-bca6-e95dd3018f9b.png">

<img width="851" alt="Screenshot 2022-03-08 at 14 11 11" src="https://user-images.githubusercontent.com/79321645/157244917-b8f05c61-94f8-412c-a856-47f33c94d59b.png">

