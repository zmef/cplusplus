## Flowchart for Average Students per Teacher

This Markdown file contains Mermaid code to display a flowchart for calculating the average number of students per teacher. When viewed on GitHub (or other platforms that support Mermaid), the code block below will be rendered as a graphical flowchart with standard flowchart shapes.

```mermaid
graph TD
    A(Start) --> B[Input Number of Students];
    B --> C[Input Number of Teachers];
    C --> D{Calculate Average = Number of Students / Number of Teachers};
    D --> E[Display Average];
    E --> F(End)
    A(Start):::startEnd
    F(End):::startEnd
    B[Input Number of Students]:::inputOutput
    C[Input Number of Teachers]:::inputOutput
    E[Display Average]:::inputOutput
    D{Calculate Average = Number of Students / Number of Teachers}:::process

    classDef startEnd fill:#f9f,stroke:#333,stroke-width:2px,shape:ellipse
    classDef inputOutput fill:#ccf,stroke:#333,stroke-width:2px,shape:rect
    classDef process fill:#fff,stroke:#333,stroke-width:2px,shape:rect
