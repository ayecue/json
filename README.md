# JSON

Supports basic json parse and stringify in greyscript. Example project for greybel.

# Usage

```js
myJsonStr = JSON.stringify({ "test": 123 })

print(myJsonStr) // prints json string
print(JSON.parse(myJsonStr)) // prints object
```

# How to install

You require either [greybel-js](https://github.com/ayecue/greybel-js) or [greybel-vs](https://github.com/ayecue/greybel-vs).

## Via greybel-js

- Execute following command `greybel ./src/json.src . -i`
- Copy paste the content of `./build/installer0.src` into GreyHack CodeEditor.exe
- Execute build in CodeEditor.exe, this should install all files
- Open the json.src file via the CodeEditor.exe and build it as a library for you to use

## Via greybel-vs

- Open `./src/json.src` in VS and press execute a build via the context menu
- Copy paste the content of `./build/installer0.src` into GreyHack CodeEditor.exe
- Execute build in CodeEditor.exe, this should install all files
- Open the json.src file via the CodeEditor.exe and build it as a library for you to use

# How to test

```bash
greybel-execute ./test/index.src
```