# Jquery Elimore
#### Make Easy For Ellipsis Text

Elimore is jQuery that help you to make ellipsis text for multiple line of text with view or more button. You can trim how long the character will show.

---

## Usage

Required jQuery before calling elimore.

1. Include jquery.elimore.js in your project files
2. Call the elimore
### Default options
```
$(element).elimore();
```
### Show Text Only Without Hidden Button.
```
$(element).elimore({showOnly:true})
```
---

## Options

```
maxLength:130, // int (default value is 130)
moreText : "More View", // string
lessText : "Less View", // string
showOnly : false // boolean
```



