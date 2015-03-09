##(on working)A simple lib for js lost part
pandding
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

#####ES6 feature
* Number.isFinite(v)
* Number.isInteger(v)
* Number.isNaN(v)
* Number.isSafeInteger()
* Number.EPSILON

#####Additional


####Math

#####ES6 feature
* Math.clz32(v)
* Math.imul(v)
* Math.trunc
```js
Math.trunc(4.1) // 4
Math.trunc(4.9) // 4
Math.trunc(-4.1) // -4
Math.trunc(-4.9) // -4
```
* Math.sign
```js
Math.sign(-5) // -1
Math.sign(5) // +1
Math.sign(0) // +0
Math.sign(-) // -0
Math.sign(NaN) // NaN
```
* Math.log10(x)
* Math.log2(x)
* Math.log1p(x)
* Math.expm1(x)



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

#####ES6 feature
* Array.from
* Array.of
* find
* findIndex
* fill

#####Additional
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

#####ES6 feature
* Object.getOwnPropertyDescriptors(o,p)
* Object.getPropertyDescriptor(o,p)
* Object.getOwnPropertyNames(o)
* Object.is(a, b)
* Object.setPrototypeOf(o, proto)
* Object.assign(target, source1, source2, …)

#####Additional
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
