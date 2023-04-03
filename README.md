```mermaid
graph LR
A[Start] --> B[Process 1]
B --> C[Process 2]
C --> D[Process 3]
D --> E[End]


This will create a simple flowchart with rectangular nodes and arrows connecting them. You can customize the nodes and arrows by adjusting the syntax accordingly. Here's an example of a more complex mermaid graph with a mermaid syntax:

graph LR
A[Start] --> B{Is it morning?}
B --> |Yes| C[Have breakfast]
C --> D[Get dressed]
D --> E[Go to work]
B --> |No| F{Is it afternoon?}
F --> |Yes| G[Have lunch]
G --> D[Get dressed]
F --> |No| E[Go to work]
E --> H[Do work]
H --> I[Go home]
I --> J[Relax]
J --> K[Sleep]


This creates a more complex flowchart with diamond-shaped decision nodes, rectangular process nodes, and arrows with labels. You can adjust the syntax and elements to create a mermaid graph that fits your needs.
