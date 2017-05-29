### Scope

* Variables are scoped to the closest `{`
* When accessing a variable, the runtime will go up the stack until a `{` or it exhausts all stack frames


### Variable Scope outside of class
| Keyword | Description |
| ------- | ----------- |
| `local` | Only the current Namespace can access |
| `global` | Anything can access |

### Variable Scope inside of class
| Keyword | Description |
| ------- | ----------- |
| `public` |  |
| `protected` |  |
| `private` |  |