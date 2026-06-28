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

## Day 46 — 2026-04-21

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

## Day 50 — 2026-04-25

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

## Day 54 — 2026-04-29

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

## Day 58 — 2026-05-03

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

## Day 62 — 2026-05-07

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

## Day 66 — 2026-05-11

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

## Day 70 — 2026-05-15

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

## Day 74 — 2026-05-19

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

## Day 78 — 2026-05-23

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

## Day 82 — 2026-05-27

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

## Day 86 — 2026-05-31

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

## Day 90 — 2026-06-04

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

## Day 94 — 2026-06-08

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

## Day 98 — 2026-06-12

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

## Day 102 — 2026-06-16

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

## Day 106 — 2026-06-20

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

## Day 110 — 2026-06-24

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

## Day 114 — 2026-06-28

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
