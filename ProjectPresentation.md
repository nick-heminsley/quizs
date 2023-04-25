---
marp: true
theme: quiz
footer: "Nick Heminsley"
style: |
  img[alt~="centre"] {
    display: block;
    margin: 0 auto;
  }
---

# Project Lead - Bulk Offers UI: Overcoming Adversity and Delivering Success

Nick Heminsley

---

# Introduction

---

## Project Overview

- Project Lead: Bulk Offers UI (Jan 2023 - May 2023)
- Goal: Develop a new trader UI for bulk editing of offers
- Stakeholders: UX designers, trading team, management

---

# Situation

---

## Business Problem

- Inefficient and time-consuming bulk offer editing process for traders

---

## Objective

- Create a user-friendly, efficient, and responsive UI for bulk offer editing

---

# Task

---

## Individual Responsibilities

- Planning, and coordinating communication with UX and traders, development lead
- Pairing and teaching the new graduate on the project
- Mentoring the team in good angular practices

---

## Architecture

- Front end Angular 12 UI
- Java 17 API layer application
- Java 17 Spring Boot microservice
- MySql Database

---


## Team Members

- UX designer, 4 full-stack developers

---

## Daily Activities

- Meetings, delegating tasks, tracking progress, resolving issues, hands-on development

---

# Project Execution

---

## Phase 1: Ideation, UX designs and planning

- Organising initial workshopping days. 
<!-- Two days in the office planning, researching competition, going through what we want the new UI to achieve -->
- Went through 5 iterations of UX. Each week we have a meeting to go through each design talking about what we want for MVP and what features we'd consider as nice to have. Then we'd test with traders to get opinions on the new flow
- We spent a lot of time improving the name of different parts of the object. In the old UI, the names were just based on what they were in the database but I wanted to focus on improving the user experience and building a UI that spoke for itself
- Writing out the first two sprints worth of tickets. Breaking down the required components so that tickets can be done in parallel. Looking at the new endpoints and objects required. 
- After each sprint write new sets of tickets based on changing requirements/designs etc

---

## Phase 2: Technical Development

- Setting up the base UI with routing and service to retrieve data.
- Creating a set of mock endpoints to allow ticket parallelisation
- Handling Data with RXJS observables
- Using FormControls to handle user input
- Creating 6 Jetty endpoints that connect the DB to the UI.
- Handling complex logic around validating multiple updates across different objects.

---

# Result

---

## Project Outcome

- Completed MVP a month before the deadline.
- Testing with traders showed lots of positive feedback around new designs and flows.
- New UI will improve productivity and reduce wasted time from the traders.
- "It's very clear which sections I've adjusted and which I haven't."
- “Process is clear and submitting the bulk adjustment is clear as well.”

---

## Lessons Learned

- Better able to break down a project into manageable chunks.
- Knowledge of angular FormControls and RXJS drastically improved
- Delving into Jackson object mappers for complex objects, looking at how they work with records and interfaces.

---

## Adjustments

- Take more time expanding descriptions on tickets so that other people have more guidance on the scope of the ticket
- Check to see if object design will map with Jackson and how it will deserialise it
- Ensuring UX designs are all collated at the end of all iterations

---

# Conclusion

---

## Bulk Offers UI

- A successful project that showcases resilience and adaptability

---

## Relevance to the Role

- Demonstrates strong project management skills, technical expertise, and ability to lead teams through challenges

---

## Personal Growth

- Enhanced leadership skills, ability to learn from past experiences and skills in object and architecture design.
