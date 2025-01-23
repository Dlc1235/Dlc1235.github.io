# **Guessing.md**
This is my lab 2 guessing game using mermaid to visually show how it works.
```mermaid
flowchart TD
  Start([Start]) --> B(Generate a random integer between 1 and 10)
B --> C(Guess  3)
C --> D(If integer) & E(If not integer)
E --> B
D --> F(Higher)
F --> H(Guess 8)
H --> I(Correct)
I -->J([End])
```
User starts the game then chooses a integer between 1 and 10. The User chooses the integer 3 and the game continues. If the user does not choose a integer then the game will restart. If the users guess was to low the user must choose a higher integer. If the user chooses the correct number then the game ends.
