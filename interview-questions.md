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

## Day 8 — 2026-03-15

### 🎯 Interview Q: What is the difference between HashMap and Hashtable?

**Answer:**

| Feature | HashMap | Hashtable |
|---|---|---|
| Thread Safe | ❌ No | ✅ Yes (synchronized) |
| Null Keys | ✅ 1 null key allowed | ❌ Not allowed |
| Performance | ✅ Faster | ❌ Slower |
| Preferred | ✅ Modern code | ❌ Legacy |

```java
// Prefer HashMap in single-threaded apps
Map<String, Integer> map = new HashMap<>();
map.put(null, 1);  // works fine

// Use ConcurrentHashMap for thread-safe modern code
Map<String, Integer> safe = new ConcurrentHashMap<>();
```
> 💼 **Tip:** If asked about thread safety, mention  as the modern alternative.

## Day 12 — 2026-03-18

### 🎯 Interview Q: What is the difference between HashMap and Hashtable?

**Answer:**

| Feature | HashMap | Hashtable |
|---|---|---|
| Thread Safe | ❌ No | ✅ Yes (synchronized) |
| Null Keys | ✅ 1 null key allowed | ❌ Not allowed |
| Performance | ✅ Faster | ❌ Slower |
| Preferred | ✅ Modern code | ❌ Legacy |

```java
// Prefer HashMap in single-threaded apps
Map<String, Integer> map = new HashMap<>();
map.put(null, 1);  // works fine

// Use ConcurrentHashMap for thread-safe modern code
Map<String, Integer> safe = new ConcurrentHashMap<>();
```
> 💼 **Tip:** If asked about thread safety, mention  as the modern alternative.

## Day 16 — 2026-03-22

### 🎯 Interview Q: What is the difference between HashMap and Hashtable?

**Answer:**

| Feature | HashMap | Hashtable |
|---|---|---|
| Thread Safe | ❌ No | ✅ Yes (synchronized) |
| Null Keys | ✅ 1 null key allowed | ❌ Not allowed |
| Performance | ✅ Faster | ❌ Slower |
| Preferred | ✅ Modern code | ❌ Legacy |

```java
// Prefer HashMap in single-threaded apps
Map<String, Integer> map = new HashMap<>();
map.put(null, 1);  // works fine

// Use ConcurrentHashMap for thread-safe modern code
Map<String, Integer> safe = new ConcurrentHashMap<>();
```
> 💼 **Tip:** If asked about thread safety, mention  as the modern alternative.
