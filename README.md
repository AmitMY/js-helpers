# js-prototypes
Important although missing Javascript prototypes

# Contribution
Think there is an important, useful prototype that is missing? Let us know by opening an issue.

## Note:
The object prototypes can be used on all object extensions.

## How to use?
- Install: `npm install --save js-prototypes`
- Include the repo:
    - ES6: `import JSPrototypes from "js-prototypes"`
    - NodeJS: `var JSPrototypes = require("js-prototypes")`
- Execute the prototypes:
    - `JSPrototypes.all()` will add all prototypes
    - `JSPrototypes.object()` will add all object prototypes
    - `JSPrototypes.array()` will add all array prototypes
    - `JSPrototypes.string()` will add all string prototypes
    
## Available prototypes

---

### Object
Method|Description
------|-----------
size(obj)|How many properties does an object have
clone(obj)|Value level cloning of non-circular objects
values(obj|Converts an object to an array of values. Proposed for ES7
forEach(obj, callback(value, key))|Loops through an object, and executes a callback

---

### Array
Method|Description
------|-----------
shuffle()|Shuffles an array
top()|Top of the array, without popping
unique()|Returns an array of unique values, with no order changes

---

### String
Method|Description
------|-----------
capitalise()|Capitalises a string

---

### Element
Method|Description
------|-----------
data()|Returns an object with the element's data
data(key)|Returns the data with given key, or throws an exception
data(key, value)|Sets element data `key` to be `value`