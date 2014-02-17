# Concurix modifications/enhancements to the standard Node.js style guide.

## Filenames

Since Concurix runs on multiple platforms, and not all of them support case sensitivity, file names should use a snake case
naming convention.

Example:
```js
foo_bar.js
```

## JSON key names

Similarly, as Concurix supports multiple programming languages, snake case should be used in json key names for better interoperability with Ruby, Erlang, etc. 

Example: 

```js
{
  "foo_bar": 1,
  "bar_id": 2
}
```