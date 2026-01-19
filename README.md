# HowMuchPer

**HowMuchPer** is a small utility project that converts a value expressed in one time unit into equivalent values across other time units.

You provide a number and its base interval (e.g. per minute, per day, per year), and the app calculates what that number looks like per second, hour, day, month, and year.

---

## What it does

Given:

* a numeric value
* a base time unit (second, minute, hour, day, month, year)

It calculates:

* per second
* per minute
* per hour
* per day
* per month
* per year

The logic is deterministic and purely mathematical — no external data sources.

---

## Example

```
Input:
1000000 per year

Output:
≈ 83,333.33 per month
≈ 2,739.73 per day
≈ 114.16 per hour
≈ 1.90 per minute
≈ 0.03 per second
```

---

## Use cases

* sanity-checking large numbers
* comparing metrics across different time scales
* quickly understanding magnitude and scale
* small educational or visualization projects

---
