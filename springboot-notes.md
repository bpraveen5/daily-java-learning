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

## Day 6 — 2026-03-15

### 🍃 Spring Boot: @RestController vs @Controller
```java
// @Controller — returns VIEW name (for HTML pages)
@Controller
public class PageController {
    @GetMapping("/home")
    public String home() {
        return "home";  // looks for home.html template
    }
}

// @RestController = @Controller + @ResponseBody
// Returns JSON/XML directly (for APIs)
@RestController
@RequestMapping("/api")
public class ApiController {
    @GetMapping("/users")
    public List<User> getUsers() {
        return userService.findAll();  // returns JSON
    }
}
```
> 🔑 **Rule:** Use  for REST APIs. Use  for MVC web pages.
