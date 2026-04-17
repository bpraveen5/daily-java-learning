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

## Day 10 — 2026-03-16

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

## Day 14 — 2026-03-20

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

## Day 18 — 2026-03-24

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

## Day 22 — 2026-03-28

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

## Day 26 — 2026-04-01

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

## Day 30 — 2026-04-05

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

## Day 34 — 2026-04-09

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

## Day 38 — 2026-04-13

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

## Day 42 — 2026-04-17

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
