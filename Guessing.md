```mermaid
flowchart TD



 Start([Start]) --> A(Declare Random Variable) --> B(Assign value randomly between 1 and 100) --> C(Ask player a guess between 1 and 100) --> Evaluation{Evaluate the answer} --> D(User is correct) --> End([End])

Evaluation --> |higher| E[Inform user its number is higher than the number to guess]
Evaluation --> |lower| F[Inform user its number is lower than the number to guess]

E --> C
F --> C



```