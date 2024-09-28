```mermaid
flowchart TD



 Start([Start]) --> A(Declare Random Variable) --> B(Assign value randomly) --> C(Ask player a guess) --> D(User is correct) --> End([End])

C --> D(User said a higher number)
C --> D(User said a lower number)
C --> D(User said a higher number)

```