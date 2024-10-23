# Application 1: Rule Engine with AST

> **Zeotap | Software Engineer Intern | Assignment | Application 1**

## Applicant Introduction

Hi, I'm **Harshita S R**, a dedicated and versatile digital media professional with a solid foundation in both **front-end and back-end development**. With experience working on **full-stack technologies**, I have knowledge of front-end frameworks like **HTML, CSS, and JavaScript**, along with proficiency in back-end technologies such as **Node.js, Python**, and databases like **SQL and NoSQL**. I’m also passionate about optimizing models, such as **RAG with OpenAI** and **Pinecone DB**, and continuously strive to stay updated on emerging trends in **web and app development**.  

---

## Table of Contents

- [Introduction](#introduction)
- [Technical Parts](#technical-parts)
  - [Installation](#installation)
  - [How to Run](#how-to-run)
- [About Solution](#about-solution)
  - [Solution Overview](#solution-overview)
  - [Code Structure](#code-structure)
- [Non-Technical Parts](#non-technical-parts)
  - [My Approach](#my-approach)
  - [Feedback](#feedback)
- [Outro](#outro)

---

## Introduction

I read the assignment description several times to ensure I didn’t miss anything.  
Here are some key points about the code and the documentation:

- The code is heavily commented with docstrings (React code is compatible with Doxygen, and Python code with Sphinx).
- Unit tests cover both **positive** and **negative** cases, aiming for **80%+ coverage**.
- This README explains the **technical parts** first, followed by a discussion of the **solution** and concludes with **non-technical reflections**.

---

## Technical Parts

### Installation

The entire solution is containerized using **Docker** for platform-agnostic deployment. However, you can also run the components separately on your local machine.

#### Frontend
```bash
cd frontend
npm install
npm start
