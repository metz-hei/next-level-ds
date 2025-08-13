# Test File

This is a test file with some markdown linting errors.

## Bad Heading

This heading has trailing punctuation.

### Bad Indentation

This heading has extra spaces.

- Bad list indentation
- More bad indentation

```javascript
console.log("This code block is fine");
```

But this one has no language specified:

```javascript
console.log("This should trigger an error");
```
