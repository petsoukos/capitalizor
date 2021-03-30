# Capitalizor

## The script "Camel Cases" an input string.
## Make the first letter of each word of a string uppercase.

When the first letter of each word is an uppercase character, then we say that the string is Camel Cased.

### examples:
"upper case" -> "Upper Case"
"camel case" -> "Camel Case"

```
function capitalizor(words) {
    let string = words.split(" ");
    for(let i = 0; i < string.length; i++) {
        string[i] = string[i][0].toUpperCase() + string[i].substr(1);
    }
    return string.join(" ");
}
```
