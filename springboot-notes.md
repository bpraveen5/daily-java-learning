# 🍃 Spring Boot Notes

> Daily Spring Boot notes added automatically. One note per rotation cycle.

---

## Day 2 — Getting Started

### 🍃 Spring Boot: What is @SpringBootApplication?

```java
@SpringBootApplication  // = @Configuration + @EnableAutoConfiguration + @ComponentScan
public class MyApp {
    public static void main(String[] args) {
        SpringApplication.run(MyApp.class, args);
    }
}
```

> 🔑 **Key:** `@SpringBootApplication` is the entry point. It auto-configures everything Spring needs.

---
