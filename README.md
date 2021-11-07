# css-in-depth
Repo includes personal notices and examples from book "CSS in Depth"

## Basic terminology

This is called a **declaration**:
```
color: black
```

`color` is a property. Don't confuse properties with HTML attributes, which are attributes of an HTML tag:

```
<a href="..">
```

Group of **declaration**s is called **declaration block**:

```
body {
    background: red;
    font-family: sans-serif;
}

```

Together the selector (`body`) and the declaration block (`{....}`) are called a **rule set**.