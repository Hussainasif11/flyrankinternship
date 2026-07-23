# Implementation Plan - Workflow Audit & Tool Setup (FL-01)

This plan outlines the creation of the 1 to 2 page Workflow Audit, target tasks definition, and verification of the tool setup as requested in the FL-01 brief.

## Open Questions

> [!IMPORTANT]
> To ensure the tasks are genuinely yours (and pass the evaluation criteria), please review the proposed tasks below and indicate if you'd like to adjust, replace, or add any.

1. **Task Personalization**: Are the 12 candidate tasks listed below representative of your actual week, or would you like to swap any for other specific study/work/side-project tasks?
2. **Toolkit Setup Evidence**: Have you already set up ChatGPT, Claude, and Anthropic Academy accounts? If you have a screenshot of your configured Claude Project or any other screenshots, where are they located on your system so I can copy/link them to the deliverable? If not, would you like me to guide you through creating the Custom Instructions or creating a placeholder in the document for you to embed the screenshot later?
3. **Claude Project Custom Instructions**: Who are you, what are your tone preferences, and what are your current goals? I can draft a premium set of custom instructions based on your background in web/ML development, but let me know if you have specific preferences.

---

## Proposed Changes

We will create a comprehensive markdown document `workflow_audit.md` in the workspace root (`c:/Users/hussa/Desktop/ml/workflow_audit.md`) which will serve as the primary deliverable containing the table, target tasks, and setup evidence.

### Workspace Document

#### [NEW] [workflow_audit.md](file:///c:/Users/hussa/Desktop/ml/workflow_audit.md)
- Contains the **Workflow Audit Table** with 10-15 tasks classified according to the Ethan Mollick framework ("just me", "delegate to AI with review", "collaborate with AI", "fully automate"), each with a one-line rationale.
- Incorporates at least 2 tasks marked "just me" with honest human-centric reasons.
- Contains the definitions for **Three Target Tasks** that will be reused in FL-02 through FL-04, detailing what "done well" means for each with measurable success criteria.
- Includes a section documenting the **Tool Setup Verification** (Claude, ChatGPT, Anthropic Academy) and displaying/referencing the configured Claude Project instructions and screenshot.

---

## Candidate Tasks for Audit

Based on your active projects (the Online Examination System `littlesoul` with React/Express, and the `ml` workspace), here are 12 proposed recurring tasks for your audit:

| Task Name | Classification | Rationale |
| :--- | :--- | :--- |
| **1. UI Component Styling & Layout** (e.g. styling `Admin.jsx` or `Footer.jsx`) | Collaborate with AI | AI generates responsive CSS/layouts quickly, but manual tweaks are needed for precise brand alignment. |
| **2. Debugging React State & Lifecycle Errors** | Delegate to AI with review | AI is excellent at explaining stack traces and suggesting fixes, which I review before applying. |
| **3. Writing Express.js API Endpoints & DB Queries** | Collaborate with AI | AI boilerplates the routing, while I ensure security, proper DB schema usage, and input validation. |
| **4. Architectural System Design** | Just Me | Deciding overall database design, authorization flows, and project architecture requires deep context and responsibility. |
| **5. Reading & Summarizing ML Research Papers** | Collaborate with AI | AI quickly extracts key architectures and math from PDFs, which I verify against my own reading. |
| **6. ML Model Training Environment Setup** (PyTorch/CUDA setup) | Delegate to AI with review | AI provides the exact command sequences for dependency alignment, which I check against my local hardware constraints. |
| **7. Writing Unit & Integration Tests** | Fully Automate | AI can auto-generate extensive test suites from component files based on standard patterns, saving boilerplate time. |
| **8. Code Reviewing PRs** | Delegate to AI with review | AI highlights syntax inefficiencies and edge cases, but I must perform the final logical sign-off. |
| **9. Academic Study Planning & Scheduling** | Just Me | Managing my own learning pacing, cognitive load, and motivation is highly personal and cannot be outsourced. |
| **10. Writing Release Notes / Documentation** | Collaborate with AI | AI drafts descriptions from commit messages, while I polish the tone to be professional and clear. |
| **11. Refactoring Legacy Code / Technical Debt** | Collaborate with AI | AI suggests patterns (e.g., custom hooks), and I evaluate if the changes break existing features. |
| **12. Client/User Feedback Synthesis** | Delegate to AI with review | AI clusters bulk user reviews into theme buckets, which I analyze to decide feature prioritization. |

---

## Verification Plan

### Manual Verification
- Review the compiled `workflow_audit.md` to ensure it fits the 1-2 page scope when rendered.
- Check that all evaluation criteria are met (10+ genuine tasks, one-line rationales, two "just me" classifications, three target tasks with measurable success criteria, accounts setup evidence).
- Ensure the image link for the Claude Project screenshot correctly references a file (e.g. `claude_project_screenshot.png`) that is saved in the workspace.
