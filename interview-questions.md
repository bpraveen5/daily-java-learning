# 🎯 Interview Questions & Answers

> Daily interview Q&A added automatically. One question per rotation cycle.

---

## Day 4 — Getting Started

### 🎯 Q: What are the 4 pillars of OOP?

**Answer:**

| Pillar | Meaning | Java Example |
|--------|---------|-------------|
| **Encapsulation** | Hide data using private fields + getters/setters | `private int age;` |
| **Inheritance** | Child class inherits parent class | `class Dog extends Animal` |
| **Polymorphism** | One method, many forms | Method overriding / overloading |
| **Abstraction** | Hide implementation, show only what's needed | `abstract class` / `interface` |

```java
// Polymorphism Example
Animal a = new Dog();   // Dog IS-A Animal
a.makeSound();          // calls Dog's version of makeSound()
```

> 💼 **Tip:** Always give a real Java code example in interviews — it shows practical knowledge.

---
