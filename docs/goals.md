--- 
layout: default
title: Goals
nav_order: 1
--- 

# Goals
```mermaid
flowchart TD
    A[init] -->|After initialization| B[Search]
    B --> C[Screen]
    C --> D[Synthesize]
    D --> B
    D -->|When ready| E[Publish Results]
```
