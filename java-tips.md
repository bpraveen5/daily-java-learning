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
