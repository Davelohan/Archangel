---
name: skill-meta-planner
description: Scrutinize all skills in the repository and plan coordinated execution for user requests, ensuring the most relevant skill(s) are applied in the correct order and context.
---

# Skill Meta-Planner

## Purpose
Analyze all available skills in the repository and plan their coordinated use to address user requests, ensuring each skill is applied in the optimal sequence and context.

## Step-by-Step Process
1. **Skill Inventory**
   - List all skills in the repository, summarizing their purpose and scope.
2. **Request Analysis**
   - Parse the user’s request to identify relevant legal, canonical, ethical, or procedural domains.
3. **Skill Matching**
   - Select the most relevant skill(s) for the request.
   - Determine the correct order of execution if multiple skills are needed.
4. **Execution Plan**
   - Outline a step-by-step plan for applying the selected skills.
   - Specify input/output handoffs between skills if required.
5. **Review and Adjust**
   - After execution, review results and suggest further actions or additional skills if needed.

## Output Format
- Inventory of available skills
- Matched skills for the request
- Step-by-step execution plan
- Review and recommendations

## Example Use
- User describes a complex situation involving canon law, civil law, and bullying.
- The meta-planner identifies and sequences the relevant skills (e.g., canon-law, civil-law, countermeasures).
- Provides a coordinated plan for analysis and response.
