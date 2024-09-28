```mermaid
flowchart TD

Start([Start]) --> A(Declare Random Variable) --> B(Assign value randomly between 1 and 100) --> C(Ask player a guess between 1 and 100) --> Validation{Is it a number between 1 and 100?}   

Validation --> |Yes| Evaluation{Evaluate the answer}
Validation --> |No| C

Evaluation --> |higher| E[Inform user its number is higher than the number to guess]
Evaluation --> |lower| F[Inform user its number is lower than the number to guess]
Evaluation --> |correct| G[Inform the user that it's correct]

E --> C
F --> C
G --> End([End])

```

<!--

The process follows a flow from START to END with two moments when the answer of the user is evaluated.
In the first one, validation, the system evaluate if the answer is a number between 1 and 100. If so, it continues. If not, it ask the user a number again
In the second one, evaluation, the system evaluate if the answer is correct. If so, it goes to END. If not, it informs the user iif its guess is lower or higher than the number to guess and ask the user a number again

-->