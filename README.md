# Capitalizor

## Make first letter of each word of a string uppercase

### example:
"upper case" -> "Upper Case"

```
function capitalizor(words) {
    let string = words.split(" ");
    for(let i = 0; i < string.length; i++) {
        string[i] = string[i][0].toUpperCase() + string[i].substr(1);
    }
    return string.join(" ");
}
```
