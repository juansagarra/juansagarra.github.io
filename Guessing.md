```mermaid
flowchart TD



 Start([Start]) --> A(Declare Random Variable) --> B(Assign value randomly between 1 and 100) --> C(Ask player a guess between 1 and 100) --> Evaluation --> D(User is correct) --> End([End])

Evaluation --> |higher| E[(Inform user its number is higher than the number to guess)]


```