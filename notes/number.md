## NUMBER

Supports underscores.

```kotlin
val oneMillion = 1_000_000
val ssn = 999_99_9999L
val hexBytes = 0xFF_EC_DE_5E
val bytes = 0b01110101_00001110
```

## Boxing

`Number` is superclass for all classes representing numeric values. Assigning value to type `Number` needs object wrapper, also called boxing.

```kotlin
val boxed: Number = 2
boxed.toLong() * 3
```
