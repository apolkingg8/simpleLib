##(on working)A simple lib for js lost part
---

###Todo list(add on prototype...or not?)
---

####Type Check
- isElement
- isArray
- isObject
- isArguments
- isFunction
- isString
- isNumber
- isFinite
- isBoolean
- isDate
- isRegExp
- isNaN
- isNull
- isUndefined

####Number
* #####ES6 feature
  * parseInt
  * parseFloat

####Math
  * Math.trunc //es6
  ```js
  Math.trunc(4.1) // 4
  Math.trunc(4.9) // 4
  Math.trunc(-4.1) // -4
  Math.trunc(-4.9) // -4
  ```
  * Math.sign //es6
  ```js
  Math.sign(-5) // -1
  Math.sign(5) // +1
  Math.sign(0) // +0
  Math.sign(-) // -0
  Math.sign(NaN) // NaN
  ```


####String
#####ES6 feature
* fromCodePoint
* codePointAt
* repeat
* startsWith
* endWith
* contains

#####Additional
* trim()
* trimLeft()
* trimRight()
* replaceAll()
* toDate(dateFormate)
* isBlank() `'/n', ' ', '/r', ect...`  
* join()
* hasChars(chars)
* replaceChars(chars)
* isUrl()
* isEmailAddr()

####Array
* clone()
* inArray()
* sortBy()
* indexOf() //return num or [nums]
* union()
* intersection()
* difference()
* first(num)
* last(num)
* without(string or num)

####Object
* clone()
* getKeys()
* getOwnKeys()
* getAllKeys() //include childrens
* getKeysByValue() //return array

####JSON
* clone()
* findObjByKey()
* findObjByValue()
* findObjByValue()

####DateTime
* toDateString(format)
*

####Browser
* (shit here)

####Others
* Klass function
* *.hash()
* *.equalWith()
