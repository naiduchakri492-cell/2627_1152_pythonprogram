1. PROBLEM STATEMENT
To write a Python program to print all numbers from 1 to N using for loop. Value of N is taken from the user.
2. ALGORITHMjavascript1. Start
2. Input N
3. Initialize loop variable i = 1
4. Repeat until i <= N:
      a. Print i
      b. i = i + 1
5. Stop3. FLOWCHART
START -> INPUT N -> CHECK i<=N? -> YES -> PRINT i -> LOOP BACK -> NO -> END
7. MERMAID FLOWCHART CODE
Paste this in mermaid.live to generate diagram for your PDF:mermaidgraph TD
    A([Start]) --> B[/Enter N/]
    B --> C[Set i = 1]
    C --> D{i <= N ?}
    D -->|Yes| E[Print i]
    E --> F[i = i + 1]
    F --> D
    D -->|No| G([End])Simple Mermaid Code for PDF:mermaidflowchart TD
    A([START]) --> B[/Input N/]
    B --> C[[For i=1 to N]]
    C --> D[Print i]
    D --> C
    C --> E([STOP])
