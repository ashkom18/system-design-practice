# Capacity Estimation

For a system-design interview, estimate traffic and storage before choosing infrastructure.

## Example

Suppose an application has 1,000,000 daily users and each user makes 10 requests per day.

```text
Requests/day = 1,000,000 × 10
             = 10,000,000
```

Average requests/second:

```text
10,000,000 / 86,400 ≈ 116 RPS
```

If peak traffic is 5× average:

```text
Peak ≈ 580 RPS
```

The numbers are estimates. State assumptions clearly.
