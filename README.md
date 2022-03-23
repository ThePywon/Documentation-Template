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
    * [**Param2**](#param2)

    [//]: # (Something new got added in the last update?)
  
    <ul><li  title="Added in the latest update!"><a href="#param3"><b>Param3</b> <img src="https://imgur.com/ToMgUid.gif" width="20px" height="11px"/></a></li></ul>

  </p>
</details>

* <details><summary><a href="properties"><b>Properties</b></a></summary>
  <p>

    <ul><li title="Non-Enumerable"><a href="#prop1"><b>Prop1</b> <img src="https://imgur.com/oSU7YNt.gif" width="14px" height="12px"/></a></li></ul>
    
    <ul><li title="Readonly"><a href="#prop2"><b>Prop2</b> <img src="https://imgur.com/muzdSho.gif" width="12px" height="8px"/></a></li></ul>
    
    <ul><li title="Readonly"><a href="#prop3"><b>Prop3</b> <img src="https://imgur.com/muzdSho.gif" width="12px" height="8px"/></a></li></ul>
    
    <ul><li title="Added in the new update!&#13;Readonly"><a href="#prop4"><b>Prop4</b> <img src="https://imgur.com/ToMgUid.gif" width="20px" height="11px" title="Added in the new update!"/> <img src="https://imgur.com/muzdSho.gif" width="12px" height="8px" title="Readonly"/></a></li></ul>
    
  </p>
</details>

* <details><summary><a href="functions"><b>Functions</b></a></summary>
  <p>

    * [**MyFunc1**](#myfunc1)
    * [**MyFunc2**](#myfunc2)
 
    <ul><li title="Non-Enumerable"><a href="myfunc3"><b>MyFunc3</b> <img src="https://imgur.com/oSU7YNt.gif" width="14px" height="12px"/></a></li></ul>

  </p>
</details>

* <details><summary><a href="#events"><b>Events</b></a></summary>
  <p>

    * [**Event1**](#event1)
    * [**Event2**](#event2)

  </p>
</details>

* [**Symbols?**](#symbols)

---



# How to use?

## Description

This is where you describe what your package is about and how you expect users to use it.

## Import

### Terminal

> `npm i @org/package`

### Node.js

> ```js
> const myPackage = require("@org/package");
> ```

[//]: # (Add this if you're using the @protagonists/emitter package)

## Events

This package assumes basic knowledge of the [`@protagonists/emitter`](https://www.npmjs.com/package/@protagonists/emitter) package.  
All functions and properties imported from the emitter package are not displayed here, in doubt ***GO CHECK OUT THE DOCUMENTATION FOR THE EMITTER PACKAGE!***

---



# Constructor

[//]: # (This is where you put in an example of the implementation of the constructor, types included)

```js
myPackage(options: Object?, Param2: Number?, Param3: String?)
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



# Param2

## Description

This is where you describe what the parameter does and how it works

## Expected Value

[//]: # (this is where you specify the value type/types expected by the parameter)

> Number?

## Example

[//]: # (this is where you give a simple code example of the constructor with the parameter)

```js
const myInstance = new myPackage({}, 14);
```



<a id="param3"></a>
<h1 title="Added in the latest update!">Param3 <img src="https://imgur.com/ToMgUid.gif" width="60px" height="33px"/></h1>

## Description

This is where you describe what the parameter does and how it works

## Expected Value

[//]: # (this is where you specify the value type/types expected by the parameter)

> String?

## Example

[//]: # (this is where you give a simple code example of the constructor with the parameter)

```js
const myInstance = new myPackage({}, 27, "happy");
```

---



# Properties

# Prop1

## Description

This is where you describe what the property does and how it works

## Value

[//]: # (This is where you specify the expected returned value type/types)

```
Boolean
```

## Example

### Code:

```js
// This is where you give a simple code example for the property
```

### Ouput:

```
This is where you give the output to the above code example
```



<a id="prop2"></a>
<h1 title="Readonly">Prop2 <img src="https://imgur.com/muzdSho.gif" width="24px" height="16px"/></h1>

## Description

This is where you describe what the property does and how it works

## Value

[//]: # (This is where you specify the expected returned value type/types)

```
Number
```

## Example

### Code:

```js
// This is where you give a simple code example for the property
```

### Ouput:

```
This is where you give the output to the above code example
```



<a id="prop3"></a>
<h1 title="Readonly">Prop3 <img src="https://imgur.com/muzdSho.gif" width="24px" height="16px"/></h1>

## Description

This is where you describe what the property does and how it works

## Value

[//]: # (This is where you specify the expected returned value type/types)

```
String
```

## Example

### Code:

```js
// This is where you give a simple code example for the property
```

### Ouput:

```
This is where you give the output to the above code example
```



<a id="prop4"></a>
<h1 title="Added in the last update!&#13;Readonly">Prop4 <img src="https://imgur.com/ToMgUid.gif" width="40px" height="22px" title="Added in the last update!"/> <img src="https://imgur.com/muzdSho.gif" width="24px" height="16px" title="Readonly"/></h1>

## Description

This is where you describe what the property does and how it works

## Value

[//]: # (This is where you specify the expected returned value type/types)

```
Object
```

## Example

### Code:

```js
// This is where you give a simple code example for the property
```

### Ouput:

```
This is where you give the output to the above code example
```

---

# Functions

# MyFunc1

## Description

This is where you describe what the function does and how it works

## Syntax

```js
myInstance.myFunc1(param1: String, param2: Number?)
```

## Example

### Code:

```js
myInstance.myFunc1("test", 5);
```

### Output:

```
Undefined
```



# MyFunc2

## Description

This is where you describe what the function does and how it works

## Syntax

```js
myInstance.myFunc2(param: Boolean?)
```

## Example

### Code:

```js
myInstance.myFunc2(false);
```

### Output:

```
Undefined
```



# MyFunc3

## Description

This is where you describe what the function does and how it works

## Syntax

```js
myInstance.myFunc3(param: Number?)
```

## Example

### Code:

```js
myInstance.myFunc3(69);
```

### Output:

```
Undefined
```

---

[//]: # (Using @protagonists/emitter package)

# Events

This package uses imported properties from [`@protagonists/emitter`](https://www.npmjs.com/package/@protagonists/emitter)  
Check it out first before anything in here!

## Event1

### Description

This is where you describe when and what gets sent

### Example

```js
myInstance.on("Event1", ()=>{
  // Your code!
});
```

## Event2

### Description

This is where you describe when and what gets sent

### Example

```js
myInstance.on("Event2", ()=>{
  // Your code!
});
```

---



# Symbols?

<h2><img src="https://imgur.com/ToMgUid.gif" width="60px" height="33px"/></h2>

Added in the latest update!

<h2><img src="https://imgur.com/muzdSho.gif" width="36px" height="24px"/></h2>

Readonly

<h2><img src="https://imgur.com/oSU7YNt.gif" width="42px" height="36px"/></h2>

Non-Enumerable
