# Pre-Mortem Quality Audit: Catch Failure Before It Happens

A simple, powerful ritual to identify quality risks early before they cost you time, trust, or headlines.

Use this before every major release, architectural change, or AI-driven system launch.

---

## Duration

20–30 minutes (can be embedded in planning, design review, or WQR)

---

## Objective

Imagine the project has failed catastrophically.
Now, work backward: What went wrong?

---

## Core Audit Questions

### 1. What would make this a Harvard Business School failure case??

> Frame the nightmare scenario. System crash? Data breach? Customer churn?

---

### 2. Which quality assumption are we most wrong about??

> Assumptions about users, scale, integration, AI behavior, performance?

---

### 3. What's the earliest signal this is going wrong??

> What should we be watching for before it’s too late? Think telemetry, feedback, support tickets.

---

### 4. What if the AI looks right but is confidently wrong??

> Especially important in AI-augmented systems. What if it confidently fails?

---

## Output Template

| Risk Identified                       | Early Signal           | Confidence Level (H/M/L) | Owner |
| ------------------------------------- | ---------------------- | ------------------------ | ----- |
| e.g. Unverified user flows in AI chat | Escalations to support | Medium                   | Priya |
| e.g. Silent failure of fallback       | Spike in retries       | Low                      | Tom   |

---

## Bonus Tips

- Use the results to refine test strategy and rollout plans.
- Don’t fix everything, just **acknowledge, track, and prepare**.
- Run it with engineers, PMs, QA leads, and customer-facing reps together.

---

## When to Use It

- Before launches
- Before major migrations
- Before deploying AI/ML systems
- When you're moving too fast to feel confident
