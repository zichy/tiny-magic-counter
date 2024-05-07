# tiny-magic-counter

This is a life points counter for _Magic: The Gathering_ in under 350 bytes. It supports any number of players with changable names. [See it in action!](https://zichy.github.io/tiny-magic-counter/)

## Full Code

```html
<!DOCTYPE html><html lang=en><title>Counter</title><div><button onclick="document.querySelector('div').appendChild(document.importNode(document.querySelector('template').content, true))">Add Player</button></div><template><fieldset><legend contenteditable>Player Name</legend><input type=number value=20></fieldset></template></html>
```

## Notes

* The `<html>` tag is optional, but I decided to use it to specify a document language.
* This is meant as a joke. If you want to see a (slighty) more sophisticated attempt, check out [kaunter](https://github.com/zichy/kaunter).
