## NULLABLE

```kotlin
var s: String? = "abc"
s = null
print(s)
```

```kotlin
var listOfNullables: List<Int?> = listOf(null, null, 5)
var nullableList: List<Int>? = null
var nullableListOfNullables: List<Int?>? = null
```

## Safe Call

```kotlin
var i = bytes?.dec()
```

## `!!` Operator

Not-null assertion operator (`!!`) converts any value to non-null type and throws exception if value is null:

```kotlin
val l = s!!.length
```

## Elvis Operator

When nullable reference is not null, use it, otherwise use some non-null value:

```kotlin
val l = b?.length ?: -1
```
