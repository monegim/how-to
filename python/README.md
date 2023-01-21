# Python
1. What is the differencs between `Class method` vs `Static method`?


| Class Method | Static Method |
|---|---|
| The class method takes cls (class) as first argument. | The static method does not take any specific parameter. |
| Class method can access and modify the class state. | Static Method cannot access or modify the class state. |
| The class method takes the class as parameter to know about the state of that class. | Static methods do not know about class state. These methods are used to do some utility tasks by taking some parameters. |
| @classmethod decorator is used here. | @staticmethod decorator is used here. |

[Reference](https://www.tutorialspoint.com/class-method-vs-static-method-in-python)

