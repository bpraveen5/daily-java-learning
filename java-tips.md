# ☕ Java Core Tips

> Daily Java tips added automatically. One tip per rotation cycle.

---

## Day 1 — Getting Started

### 💡 Java Tip: Always use `.equals()` for String comparison

```java
String a = "hello";
String b = new String("hello");

System.out.println(a == b);       // false — compares references
System.out.println(a.equals(b));  // true  — compares values
```

> 🔑 **Rule:** Use `.equals()` for content comparison. Use `==` only for primitive types.

---

## Day 9 — 2026-03-15

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 13 — 2026-03-19

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 17 — 2026-03-23

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 21 — 2026-03-27

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 25 — 2026-03-31

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 29 — 2026-04-04

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 

## Day 33 — 2026-04-08

### 💡 Java Tip: String Pool & Memory
```java
// String literals go to String Pool (heap memory)
String a = "hello";  // stored in pool
String b = "hello";  // reuses same pool object
System.out.println(a == b);       // true (same reference)

// new String() always creates new object in heap
String c = new String("hello");
System.out.println(a == c);       // false
System.out.println(a.equals(c));  // true (same value)
```
> 🔑 **Key Rule:** Always use  to compare String values, never 
