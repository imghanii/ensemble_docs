For `parseInt`, `parseDouble`, see [String](String.d) functions.

### console.log

The `console.log()` function is used to print messages to the console. It can be used for debugging purposes or to display information.

**Example:**

```javascript
console.log("Hello, World!"); // Output: Hello, World!
```

### regexp.test

The `regexp.test()` function is used to test if a given string matches a regular expression pattern. It returns `true` if the string matches the pattern, and `false` otherwise.

**Example:**

```javascript
var pattern = /hello/;
var str = "Hello, World!";
console.log(pattern.test(str)); // Output: false
str = "hello, how are you?";
console.log(pattern.test(str)); // Output: true
```
### btoa

The `btoa()` function is used to encode a string in base64 format. It takes a string as input and returns a base64 encoded string.

**Example:**

```javascript
var str = "Hello, World!";
console.log(btoa(str)); // Output: SGVsbG8sIFdvcmxkIQ==
```

### atob

The `atob()` function is used to decode a base64 encoded string. It takes a base64 encoded string as input and returns the decoded string.

**Example:**

```javascript
var base64Str = "SGVsbG8sIFdvcmxkIQ==";
console.log(atob(base64Str)); // Output: Hello, World!
```