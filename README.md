# Package name

## Small description of the package goes here



# Table of content

* [**How to use?**](#how-to-use)
* <details><summary><a href="#constructor"><b>Constructor</b></a></summary>
  <p>

    * [**Options**](#options)
      * [**Prop1**](#options-prop1)  
      * [**Prop2**](#options-prop2)  
      * [**Prop3**](#options-prop3)
    * [**More**](#more)

  </p>
</details>

---



# How to use?

## Import

### Terminal

> `npm i @org/package`

### Node.js

> ```js
> const myPackage = require("@org/package");
> ```

## Description

This is where you describe what your package is about and how you expect users to use it.

---



# Constructor

[//]: # (This is where you put in an example of the implementation of the constructor, types included)

```js
myPackage(options: Object, More: Number?)
```

[//]: # (This is where you explain with more details each parameter... and their properties in the case of objects)

# Options

## Description

This is where you describe what the parameter does and how it works

## Expected Value

[//]: # (this is where you specify the value type/types expected by the parameter)

> Object

## Example

[//]: # (this is where you give a simple code example of the constructor with the parameter)

```js
const myInstance = new myPackage({
  Prop1: false, 
  Prop2: 3, 
  Prop3: "Hello!" 
});
```



<a id="options-prop1"></a>
## `Options.Prop1`

### Description

This is where you describe what the property does and how it works

### Expected Value

[//]: # (this is where you specify the value type/types expected by the property)

> Boolean?

### Example

[//]: # (this is where you give a simple code example of the constructor with the property)

```js
const myInstance = new myPackage({ Prop1: true });
```



<a id="options-prop2"></a>
## `Options.Prop2`

### Description

This is where you describe what the property does and how it works

### Expected Value

[//]: # (this is where you specify the value type/types expected by the property)

> Number?

### Example

[//]: # (this is where you give a simple code example of the constructor with the property)

```js
const myInstance = new myPackage({ Prop2: 5 });
```



<a id="options-prop3"></a>
## `Options.Prop3`

### Description

This is where you describe what the property does and how it works

### Expected Value

[//]: # (this is where you specify the value type/types expected by the property)

> String?

### Example

[//]: # (this is where you give a simple code example of the constructor with the property)

```js
const myInstance = new myPackage({ Prop3: "some text" });
```



# More

### Description

This is where you describe what the parameter does and how it works

### Expected Value

[//]: # (this is where you specify the value type/types expected by the parameter)

> Number?

### Example

[//]: # (this is where you give a simple code example of the constructor with the parameter)

```js
const myInstance = new myPackage({}, 14);
```
