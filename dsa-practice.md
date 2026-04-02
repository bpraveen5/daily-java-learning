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
