---
title: Home
layout: home
---
#   Just The Docs Test Homepage

This document should contain just the overview text and a list of contents

Not yet sure how it integrates with the ReadMer.md file. 
In the original clone the Index.md and ReadMe.md files looked to be copies of each other whioch is a maintenance overhead I don't need.

Hopefully I'll find a way to integrate those two files to avoid duplication.

##  Test for Mermaid Class Diagram 

```mermaid
classDiagram 

    class Person
    class Society
    class BeneficialService
    class RegulatoryBody
    class Constitution
    
    Person --> Society : is a member of
    RegulatoryBody --> Society : manages
    Person --> RegulatoryBody : serves on
    Society --> BeneficialService : provides
    Society --> Constitution : has

%%    Society <|-- GeroPoliticalGroup : is a type of
```
