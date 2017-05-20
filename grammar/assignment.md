```

expression|value AssignModifierAssignDirection name[:Type]

```

When a new variable is created without a type, it will use the values direct type
Can optionally use a Type. If a type is assigned, the value must fit within the type bounds

####Assignment Direction

| Direction | Description |
| --------- | ----------- |
| `>` | Returns the old value |
| `<` | Returns the new value |

####Assignment Modifiers

| Modifier | Description | Allowed Target |
| -------- | ----------- | -------------- |
| `=` | Direct assign | Any |
| `+` | Add value to | Number |
| `-` | Subtracts value from | Number |
| `*` | Multiply into | Number |
| `/` | Divide into | Number |
| `%` | Mod from | Number |
| `!` | Invert | Boolean |

Errors

* Attempting to assign noVal
* Assigning the wrong Type

```

5 => temp //noVal (temp = 5)
5 +> temp //5 (temp = 10)
3 -> temp //10 (temp = 7)
2 *> temp //7 (temp = 14)
25 =< temp //25 (temp = 25)

2 *< temp //50 (temp = 50)

```

