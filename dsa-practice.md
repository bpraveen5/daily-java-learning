# 🧮 DSA Practice

> Daily DSA snippets added automatically. One problem per rotation cycle.

---

## Day 3 — Getting Started

### 🧮 DSA: Two Sum (Most Asked Interview Problem)

**Problem:** Given an array, find two numbers that add up to a target.

```java
public int[] twoSum(int[] nums, int target) {
    Map<Integer, Integer> map = new HashMap<>();

    for (int i = 0; i < nums.length; i++) {
        int complement = target - nums[i];

        if (map.containsKey(complement)) {
            return new int[]{map.get(complement), i};
        }
        map.put(nums[i], i);
    }
    return new int[]{};
}
```

> ⏱️ **Time:** O(n) | **Space:** O(n) — Classic HashMap approach!

---

## Day 7 — 2026-03-15

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 11 — 2026-03-17

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 15 — 2026-03-21

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 19 — 2026-03-25

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 23 — 2026-03-29

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 27 — 2026-04-02

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 31 — 2026-04-06

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 35 — 2026-04-10

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 39 — 2026-04-14

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 43 — 2026-04-18

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 47 — 2026-04-22

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 51 — 2026-04-26

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 55 — 2026-04-30

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 59 — 2026-05-04

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 63 — 2026-05-08

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 67 — 2026-05-12

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 71 — 2026-05-16

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 75 — 2026-05-20

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 79 — 2026-05-24

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 83 — 2026-05-28

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 87 — 2026-06-01

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 91 — 2026-06-05

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 95 — 2026-06-09

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 99 — 2026-06-13

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 103 — 2026-06-17

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 107 — 2026-06-21

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 111 — 2026-06-25

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 115 — 2026-06-29

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 119 — 2026-07-03

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 123 — 2026-07-07

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 127 — 2026-07-11

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 131 — 2026-07-16

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 135 — 2026-07-20

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 139 — 2026-07-24

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 143 — 2026-07-28

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 147 — 2026-08-01

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!

## Day 151 — 2026-08-05

### 🧮 DSA: Binary Search (O log n)
```java
public class BinarySearch {
    public static int search(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // avoids overflow

            if (arr[mid] == target) return mid;
            if (arr[mid] < target) left = mid + 1;
            else right = mid - 1;
        }
        return -1; // not found
    }
}
```
> ⏱️ **Time:** O(log n) | **Space:** O(1) — Must know for interviews!
