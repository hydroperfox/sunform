# Types

## Dynamic type

`*`

* Undefined = true
* Null = true

## Void type

`void`

* Undefined = true
* Null = false

## Null type

`null`

* Undefined = false
* Null = true

## Class

`class`

* Undefined = false
* Null = true

## Enum

`enum`

* Undefined = false
* Null = true

## Interface

* Undefined = false
* Null = true

## Tuple type

* Equivalent = `Array`
* Undefined = false
* Null = true

## Function type

`function(T1, T2=, ...[T3]):E`

* Equivalent = `Function`
* Undefined = false
* Null = true

## Nullable type

`T?` or `?T`

* Undefined = (compute `T`)
* Null = true

## Non nullable type

`T!`

* Undefined = (compute `T`)
* Null = false

## Argumented type

`T.<T1, TN>`

* Optimization: `Vector.<T>` where T is one of { `Number`, `uint`, `int`, `float` }.
* Undefined = false
* Null = true
