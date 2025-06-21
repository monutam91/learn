# Three-Point Estimation in Agile Projects: A Practical Summary

## Overview

Three-Point Estimation is a technique that incorporates uncertainty into effort estimation by considering multiple scenarios for a task or project: **Optimistic**, **Pessimistic**, and **Most Likely**. This method is particularly useful for estimating larger projects or epics in the early phases of Agile projects, where the details are not fully defined. By providing a range of estimates, this technique accounts for ambiguity and variability, helping teams make informed, high-level predictions.

Agile teams can use Three-Point Estimation during different phases of a project, from high-level planning of epics or quarterly goals to refinement of user stories closer to implementation. It supports Agile's **adaptive planning** principle by enabling teams to account for uncertainty and refine estimates as more information is uncovered.

---

## The Three-Point Estimation Formula

The technique evaluates three different effort scenarios per task:

1. **Optimistic Estimate (O)**: The best-case scenario—if everything goes smoothly.
2. **Pessimistic Estimate (P)**: The worst-case scenario—considering risks, blockers, or unknown variables.
3. **Most Likely Estimate (M)**: The most realistic prediction based on average conditions.

The formula to calculate the weighted average using these inputs is:

```
Estimated Effort = (O + 4M + P) / 6
```


This weighted average gives heavier importance to the "Most Likely" estimate while still incorporating the other scenarios.

---

## Using Three-Point Estimation in Agile Projects

### **1. During Project Initiation or High-Level Planning**
At the initiation phase of an Agile project, Three-Point Estimation can help provide **high-level estimates** for larger items such as **epics** or **themes**. Since details are limited, the team can estimate ranges for completion based on historical data, assumptions, and known complexities.

#### Approach:
- **Optimistic (O):** If the epic has low complexity and no unforeseen challenges.
- **Pessimistic (P):** If the epic involves unexpected risks, like technology limitations or cross-team dependencies.
- **Most Likely (M):** A reasonable estimate given what the team currently knows.

#### Example:
Epic: "Add advanced analytics dashboards."
- Optimistic (O): 50 story points (best case: functionality already exists in other modules).
- Pessimistic (P): 150 story points (unexpected integrations with external systems might delay progress).
- Most Likely (M): 100 story points.

```
Estimated Effort = (50 + (4 × 100) + 150) / 6 = 100 story points
```


This estimate can then be included as part of a **release plan** or **quarterly roadmap** for prioritization.

---

### **2. During Backlog Refinement**
In **backlog refinement sessions**, Three-Point Estimation can help provide more clarity for **large user stories** or partially defined tasks. It allows the team to evaluate the impact of known uncertainties and provides a range that Product Owners (POs) can use to refine scope.

#### Approach:
- Collaboratively identify potential blockers or uncertainties for each story.
- Assign realistic values for O, M, and P based on team discussion.

#### Example:
User Story: "Implement SSO (Single Sign-On) integration."
- Optimistic (O): 5 points (reusing existing authentication libraries).
- Pessimistic (P): 20 points (if integration with third-party service fails or requires extensive changes).
- Most Likely (M): 10 points.

```
Estimated Effort = (5 + (4 × 10) + 20) / 6 = 10.83 ≈ 11 story points
```


The estimate helps the team confidently prioritize and prepare for potential risks.

---

### **3. During Sprint Planning**
Once high-level estimates have been refined into relative measures, such as **story points**, Three-Point Estimation can be used to validate the team's **sprint scope** and ensure balance. Larger uncertainties can be flagged for discussions, creating opportunities for **spikes** or further decomposition.

- Use the variability in estimates (e.g., difference between O and P) to gauge confidence levels in the story scope.
- Funnel stories with large variability into smaller, more defined tasks to reduce risk.

---

### **4. During Risk Assessment**
Three-Point Estimation is a **risk-aware estimation method**. By explicitly considering a pessimistic case, Agile teams can better identify **risky or uncertain work** across epics or themes.

#### Example:
Epic: "Migrate billing system to the cloud."
- Optimistic (O): 100 hours (everything works as expected).
- Pessimistic (P): 400 hours (significant legacy code rewrites and unexpected compatibility issues).
- Most Likely (M): 250 hours (a realistic consideration of known challenges).

```
Estimated Effort = (100 + (4 × 250) + 400) / 6 = 250 hours
```


In this example, the large gap between optimistic and pessimistic estimates (100 vs. 400) indicates a significant degree of uncertainty. The team can flag this epic for **early discovery tasks** (e.g., spikes) to clarify risks before committing to the work.

---

## Benefits of Three-Point Estimation for Larger Projects or Epics

1. **Handles Uncertainty:** Provides a range of possible effort, ideal for dealing with poorly defined or complex epics.
2. **Supports Risk-Based Planning:** Helps identify high-risk work items by highlighting the gap between optimistic and pessimistic estimates.
3. **Improves Accuracy Over Time:** As teams refine user stories and decompose tasks, the input values (O, M, P) can become more accurate.
4. **Encourages Collaboration:** The method promotes team discussion to surface assumptions, risks, and dependencies.

---

## Situations Where Three-Point Estimation Excels

- **High-Level Planning:** For quarterly planning or roadmapping, where epics/themes need rough estimates to shape expectations.
- **Unclear or Broad Scope:** Large tasks with insufficient details, where variability is high.
- **Risk Assessment:** Tasks or projects with many unknowns or dependencies that require understanding worst-case outcomes.
- **Learning Teams:** Helps teams with less experience or varying familiarity with the systems to have a structured estimation process.

---

## Challenges and Best Practices

### Challenges:
1. **Over/Underestimations:** Relying too heavily on gut feelings or lacking historical data may skew estimates.
2. **Time-Consuming for Large Backlogs:** Estimating all items in detail with O, M, and P can become time-intensive for larger backlogs.
3. **Misjudging Risks:** Teams may underestimate the pessimistic case if risks aren't fully analyzed.

### Best Practices:
1. **Use for Larger Items:** Reserve Three-Point Estimation for epics or user stories with high uncertainty, and use simpler methods (e.g., planning poker) for smaller tasks.
2. **Focus on Accurate Inputs:** Encourage team discussions to ensure O, M, and P estimates come from shared understanding.
3. **Combine with Spikes:** For highly uncertain work, use research spikes to further refine pessimistic estimates.
4. **Identify High Variability:** Use significant gaps between optimistic and pessimistic estimates as a signal to address ambiguity early.

---

## Conclusion

Three-Point Estimation is a valuable technique for Agile teams estimating larger projects, epics, or user stories with high uncertainty. By assigning effort ranges using **Optimistic**, **Pessimistic**, and **Most Likely** scenarios, the team can account for risks and unknowns, aligning with Agile's emphasis on **adaptation and collaboration**. Use this technique during project initiation, backlog refinement, or sprint planning to efficiently manage scope, improve risk visibility, and guide prioritization in dynamic environments.
