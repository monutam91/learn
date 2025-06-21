# Estimation Techniques for Solution Architects and Teams

When working on larger projects or features, accurately estimating effort is one of the most crucial steps to ensure successful delivery. Estimation helps in setting realistic expectations, planning resources, and reducing risks. Below is a documentation of commonly used estimation techniques, summarized with examples to aid understanding for less experienced solution architects, team leads, and developers.

---

## 1. **Analogous Estimation**
Analogous estimation leverages historical data from similar past projects or features. By comparing the current work to something similar completed previously, you can estimate effort based on the effort expended in the past.

### Example:
If it took 120 hours to develop a similar e-commerce website feature like product search functionality last year, you might estimate a similar effort is required for a new feature with similar scope, such as filtering products by tags.

**When to Use:**
- When you have historical data available.
- Early stages of planning when detailed information is limited.
  
---

## 2. **Bucket System Estimation**
Bucket system estimation is a collaborative approach where tasks are assigned to predefined "buckets," which represent increasing levels of effort or complexity. It is great for sorting large numbers of items quickly.

### Steps:
 - Define effort "buckets," such as 1, 2, 5, 10, 20, 40, 100 (similar to Fibonacci numbers).
 - The team discusses and assigns each task to a bucket.
 - Optionally, refine buckets once all tasks are categorized.

### Example:
Suppose you're estimating 10 user stories:

Story 1: Fits into Bucket 1 (simple task, e.g., validation logic).
Story 2: Fits into Bucket 5 (building a new API).
Story 3: Fits into Bucket 20 (complex feature requiring integrations).

**When to Use:**

When there are many items to estimate at once (e.g., backlog grooming).
When seeking rough timeboxes quickly and efficiently.

## 3. **Bottom-Up Estimation**
Bottom-up estimation involves breaking the project into smaller tasks or components, estimating effort for each task, and summing these estimates to get the total effort.

### Example:
For a new mobile app feature:
- UI Design: 20 hours
- Backend API: 30 hours
- Integration: 15 hours
Total Estimated Effort = 20 + 30 + 15 = 65 hours

**When to Use:**
- For detailed planning when you can fully define the tasks involved.
- When you need highly accurate estimates.

---

## 4. **Three-Point Estimation**
Three-point estimation uses three values:
- **Optimistic estimate (O):** Best-case scenario if everything goes smoothly.
- **Pessimistic estimate (P):** Worst-case scenario accounting for all risks.
- **Most likely estimate (M):** Most probable scenario.

The final effort estimate is derived using the following formula:

```
Estimated Effort = (O + 4M + P) / 6
```


### Example:
Optimistic (O): 40 hours  
Pessimistic (P): 80 hours  
Most Likely (M): 60 hours  
Estimated Effort = (40 + (4 × 60) + 80) / 6 = 60 hours

**When to Use:**
- When dealing with uncertain tasks.
- To factor in risks and variability.

---

## 5. **T-shirt Sizing**
T-shirt sizing is a relative estimation technique that uses categories such as XS, S, M, L, XL to indicate the relative size or complexity of tasks. These sizes are later mapped to effort (hours or story points).

### Example:
- XS = 1 hour
- S = 5 hours
- M = 10 hours
- L = 20 hours

If a team assigns a "M" size to a task, they estimate it at around 10 hours of effort.

**When to Use:**
- During Agile/Scrum planning meetings.
- When prioritizing work rather than assigning exact effort upfront.

---

## 6. **Planning Poker**
Planning poker is a consensus-driven estimation method. Team members individually estimate effort using a deck of numbered cards (e.g., Fibonacci sequence: 1, 2, 3, 5, 8, etc.). After revealing their cards, discrepancies are discussed until consensus is reached.

### Example:
For a task of creating a new feature:
- Architect: 5 points
- Developer: 8 points
- Tester: 3 points  
The team discusses why a tester thinks the task is simpler, while the developer thinks it’s more complex. Consensus is agreed upon as 5 points.

**When to Use:**
- During Agile or Scrum estimating sessions.
- To encourage collaboration and diverse perspectives.

---

## 7. **Team Velocity**
Team velocity is an Agile technique that estimates effort based on the average amount of work (story points or tasks) completed by a team in previous sprints.

### Example:
If a team has completed an average of 40 story points per sprint over the past 3 sprints, they can estimate their capacity for the next sprint as 40 points and plan accordingly.

**When to Use:**
- In Agile environments with iterative development.
- When historical data on team performance is available.

---