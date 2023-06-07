---
layout: default
title: Analyzing Interview Data
nav_order: 3
---

# Analyzing Interview Data

To facilitate the integration of interview data into CoLRev, there is a format. Each interview is represented by an **`@interview`** block with a unique identifyer.
The interview data includes questions and corrisponding answers, identified by their question. Here's an example of the format:

`@interview{id1
    question1: {What is your position at the company?},
    answer1: {I am a developer responsible for the backend of our logistics application.},
    ...
}`

`@interview{id2
    question1: {What is your position at the company?},
    answer1: {I am a product owner in the insurance branch.},
    ...
}`

