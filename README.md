![Matrix SVG](https://raw.githubusercontent.com/rodrigograca31/rodrigograca31/master/matrix.svg)

"The Matrix [has](https://en.wikipedia.org/wiki/Has-a) you"©
```
class User:
    def __init__(self, name): self.name = name
    def __str__(self): return self.name

class Matrix:
    def __init__(self, user): self.user = user
    def reveal(self): print("The Matrix has", self.user)

Matrix(User("you")).reveal()
```
