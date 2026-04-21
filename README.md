# 🌍 Life as Objects — OOP-Based Life Simulation System

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-green)
![Maven](https://img.shields.io/badge/Maven-Build-blue)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 🧠 Overview

**Life as Objects** is a Java Spring Boot web application that models human life using Object-Oriented Programming (OOP) principles.

Instead of treating life as isolated data points, this system represents **emotions, habits, and decisions as interacting objects** that dynamically influence each other — simulating real-life behavior patterns.

---

## 🎯 Problem Statement

Traditional tracking apps:
- Treat habits, emotions, and decisions independently  
- Do not reflect real-world cause-and-effect relationships  
- Operate in a static, non-interactive way  

### ✅ Solution

This project solves the problem by:
- Modeling life components as objects  
- Allowing dynamic interaction between them  
- Generating a **Life Score** based on combined impact  

---

## 💡 Core Concept

> **“Life is a system of interacting objects.”**

Each component:
- Has its own **state (data)**  
- Has its own **behavior (methods)**  
- Interacts with other components dynamically  

---

## 🧩 Key Components

### 🧱 LifeComponent (Abstract Class)
- Base class for all life elements  
- Defines common method: `impact()`

---

## 🧠 🎓 OOP Concepts Demonstrated

- 1. Abstraction

- converted real-world ideas into code:

- Emotion
- Habit
- Decision
  
- 2. Inheritance
- LifeComponent → Emotion, Habit, Decision

- 3. Polymorphism
impact()

- Each class calculates impact differently.

- 4. Encapsulation

- Each object controls its own data:

- intensity
- consistency
- risk

- 5. Composition
- LifeSystem has many objects

- 6. Dynamic Interaction (Advanced)
- Objects influence each other at runtime.


### 😊 Emotion
- Represents emotional states (e.g., stress, happiness)  
- Attribute: `intensity (0–10)`  
- Higher intensity → stronger impact  

---

### 🏋️ Habit
- Represents behavioral patterns (e.g., gym, studying)  
- Attribute: `consistency (0–10)`  
- Reflects discipline over time  

---

### ⚠️ Decision
- Represents choices made (e.g., sleep late)  
- Attribute: `riskLevel (0–10)`  
- Higher risk → negative impact  

---

### 🧠 LifeSystem
- Stores all components  
- Calculates overall **Life Score**  

---

### ⚙️ InteractionEngine
- Handles interaction logic between objects  

**Example:**
- High stress → reduces habit consistency  
- Low stress → improves habits  

---

## 🔁 Simulation Flow

1. User adds:
   - Emotions  
   - Habits  
   - Decisions  

2. Data is stored in `LifeSystem`

3. Simulation runs:
   - `InteractionEngine` updates object states  

4. Life Score is calculated:
   - Based on all object impacts  

---

## 📊 Life Score Logic

- Positive contributions:
  - Good habits  
  - Positive emotions  

- Negative contributions:
  - Risky decisions  
  - Negative emotions  

---

## 🧠 OOP Concepts Demonstrated

| Concept        | Implementation |
|---------------|---------------|
| Abstraction   | Real-life concepts modeled as classes |
| Inheritance   | Emotion, Habit, Decision extend LifeComponent |
| Polymorphism  | Different `impact()` implementations |
| Encapsulation | Controlled data access using getters/setters |
| Composition   | LifeSystem contains multiple objects |
| Interaction   | Objects dynamically influence each other |

---

## How to Run
- save all the uploaded files in a project folder called lifeasobjects and then open file:///C:/lifeasobjects/src/main/resources/static/index.html 

## 🛠️ Tech Stack

- **Backend:** Java (Spring Boot)  
- **Build Tool:** Maven  
- **Frontend:** HTML, CSS, JavaScript  
- **API:** RESTful APIs  


---

## 🔮 Future Enhancements

- 📊 Data visualization (charts & graphs)  
- 🧠 AI-based suggestions  
- 📅 Daily simulation tracking  
- 🎮 Gamified UI  
- ☁️ Database integration  

---

## 🎤 Project Summary

This project demonstrates how Object-Oriented Programming can be applied to model complex real-world systems. By treating life components as interacting objects, it creates a dynamic simulation that reflects real-life cause-and-effect relationships, going beyond traditional static tracking applications.

---

## 👤 Author

**Antriksha Jain**


