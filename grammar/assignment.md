```

expression|value AssignModifierAssignDirection name

```

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
| `` |  |  |
| `` |  |  |
| `` |  |  |


```

5 => temp //noVal (temp = 5)
5 +> temp //5 (temp = 10)
3 -> temp //10 (temp = 7)

```