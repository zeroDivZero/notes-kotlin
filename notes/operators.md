# OPERATORS

```kotlin
1 + 1
2 - 1
2 * 3    // 6, an Int
2 * 3.0  // 6.0, a Double
1 / 2    // 0
1 / 2.0  // 0.5
```

## As Methods

```kotlin
val fish = 2
fish.plus(3)
fish.minus(3)
fish.times(3)
fish.div(3.0f)  // 0.6666667, a Float
```

## Primitive as Object

```kotlin
2.times(3)
```

## Boxing

`Number` is superclass for all classes representing numeric values. Assigning value to type `Number` needs object wrapper, also called boxing.

```kotlin
val boxed: Number = 2
boxed.toLong() * 3
```
