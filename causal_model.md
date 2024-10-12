```mermaid
graph TD
    A["Early Adoption (10 Transaction in First 7D)"]
    B["Business Capacity"]
    C["External sources"]
    D["Transaction per User 100 First 30D"]

    B ==>|Strong -ve| A
    A ==>|Strong +ve| D
    B --> D
    C --> D

    classDef strongRelation stroke:#ff3,stroke-width:4px;
    class A,B,D strongRelation;