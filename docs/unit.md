---
title: <title>
authors:
  - joe_starr
date: 2026-06-18
---

## Description

This unit describes the functionality of the module called into during a Psychopy trial.

```mermaid
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly<br>can swim<br>can dive<br>can help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }

```

### Public Interfaces

#### Interface

##### State Machine

## Unit Test Description

### Interface

#### Positive Tests

> [!test-card] "title"
>
>
> **Inputs:**
>
> **Expected Output:**
>

#### Negative Tests

> [!test-card] "Computation not executed"
>
>
> **Inputs:**
>
>
> **Expected Output:**
>
