Class Name
eg. Car
---------
Properties


------
Methods
eg. start(). stop(), move()
-----


# Class  
## How declare:

```
let bag = {
	color: "red",
	size: "small"
}
```

## How access properties/methods:

- Use dot notation:
```
	backpack.open = false
```

- UNLESS need to dynamically pass in a var at runtime, then use brackets
```
	backpack[open] = false
```





when commenting on a function in VS use:
 	/**
	update the {*} with {data-type}

WHERE TO PUT JS

put in head and use async and defer

OOP

Classes
Properties
Methods


HOW CREATE OBJ

[image:C8B19C12-2486-4346-AA2E-FCD5BFF9140B-4552-000003F10A41373D/Screenshot 2021-07-19 at 16.51.43.png]


[image:1E24F3F1-C39A-485F-A664-173EC0971749-4552-000004501BB3491A/Screenshot 2021-07-19 at 17.03.37.png]

use camelCase for property names

console.jog(obj)

do this in codepen…..
[image:DD4712EB-CC85-48BB-A420-916A6D11E9AB-4552-000005A4F18D0BEB/Screenshot 2021-07-19 at 18.53.43.png]



HOW DEFINE CLASS

class Backpack {
	constructor(color, size){
		// constructor  which sets the Backpack’s variables on initialization
		// use underscore, convention to show the property is private
		this._color = black;
		this._size = small;
	}
}

HOW MAKE A CLASS

let myBackpack = new Backpack(“black, “small”);

HOW TO ACCESS A CLASS
getter/setters

class Backpack {
	constructor(color) {
		this._color = black;
	}
	get 
}

}