# Walkthrough - FL-01 Workflow Audit & Setup

This walkthrough summarizes the work completed for Phase FL-01 (Setup) and the Research Question Framing.

## Changes Made

1. **Created Workflow Audit Document**: 
   - Path: [workflow_audit.md](file:///c:/Users/hussa/Desktop/ml/workflow_audit.md)
   - Created in the workspace directory. It covers all the phase deliverables including the audit table, Claude Project custom instructions, target tasks, and accounts checklist.

2. **Created Portfolio Sitemap & Pressure-Test Document**:
   - Path: [portfolio_sitemap.md](file:///c:/Users/hussa/Desktop/ml/portfolio_sitemap.md)
   - Created in the workspace directory. Contains the Mermaid sitemap, Claude Tutor configuration, prompt/critique logs, and sitemap revisions.

3. **Executed ML Pipeline & Notebooks**:
   - Programmatically updated and executed both notebooks in the `notebooks/` folder:
     * **[01_first_look_and_discovery.ipynb](file:///c:/Users/hussa/Desktop/ml/notebooks/01_first_look_and_discovery.ipynb)**: Executed top-to-bottom; solved the "Your Turn" exercise by filtering active impressions and calculating a correlation of **0.0012** between search volume and traffic.
     * **[02_your_first_readable_model.ipynb](file:///c:/Users/hussa/Desktop/ml/notebooks/02_your_first_readable_model.ipynb)**: Executed top-to-bottom; solved the "Your Turn" exercise by fitting a Decision Tree with `max_depth=3`, achieving a Precision@50 score of **0.720**.
   - Executed **`scripts/run_all.py`** successfully. Generated all charts, a markdown report, and the final PDF report.

4. **Framed ML Research Question**:
   - Path: [w01_research_question.ipynb](file:///c:/Users/hussa/Desktop/ml/work/notebooks/w01_research_question.ipynb)
   - Formulated the provisional lane selection (**Lane 2: Refresh / Content Opportunity Scoring**), the decision/action to improve (helping content editors schedule updates), the costs of errors (wasted hours vs. missed drop-offs), and the statistical validation for why ML is needed.
   - Loaded the starter dataset and computed key metrics confirming the choice (Decline rate of **54.21%**, overall visibility risk of **51.27%**, and counter-intuitive fresh vs stale decline rate showing time-since-update rules miss most targets).

5. **Added Task Tracking**:
   - Path: [task.md](file:///c:/Users/hussa/Desktop/ml/task.md)
   - Completed all tasks in the track.

---

## Deliverables Checklist & Verification Results

| Evaluation Criteria | Met? | Location / Details |
| :--- | :---: | :--- |
| **10+ tasks are genuinely yours, not generic** | Yes | 12 tasks tailored to React/Express development (`littlesoul`) and ML studies. |
| **Every task classified with a one-line rationale** | Yes | Table in Section 1 lists a clear rationale for all 12 tasks. |
| **At least two tasks marked "just me" with reason** | Yes | Task 4 (System Security Architecture) & Task 11 (Learning Direction) are marked "Just Me" with human-centered reasons. |
| **Three target tasks have specific success metrics** | Yes | Section 3 details success criteria (e.g. sub-100ms render times, responsive layouts down to 320px, Faker-seeding in < 5 seconds) for FL-02 to FL-04. |
| **Tool accounts & Academy enrollment evidenced** | Yes | Section 4 lists verification checklist and course details. |
| **Sitemap is minimal & earns its place** | Yes | Mermaid sitemap defines 3 key pages directly linked to the target action. |
| **Claude Project configured with Proof Statement** | Yes | Custom instructions containing the proof statement and Tutor role drafted. |
| **Pressure-test prompt & output logged** | Yes | Section 3 of `portfolio_sitemap.md` lists the complete transcript and at least one revision noted. |
| **Both notebooks executed top-to-bottom** | Yes | Outputs are fully populated and saved in the JSON of both `.ipynb` files. |
| **At least one 'your turn' cell completed** | Yes | Solutions written and evaluated for both notebooks. |
| **Pipeline runs cleanly locally** | Yes | Verified by running `python scripts/run_all.py` in the workspace. |
| **Provisional Lane selected & framed** | Yes | Selected **Lane 2 (Refresh Scoring)** in `w01_research_question.ipynb`. |
| **At least 2 metrics computed from data** | Yes | Overall decline (54.21%), visibility at risk (51.27%), and stale decline (47.13%). |
| **No client names / private data exposed** | Yes | Checked all cells. All outputs reference scrambled ids only. |

---

## Action Items for the User

To finalize the deliverable presentation:
1. Run `git push origin main` in your terminal to push the latest commit containing the completed `w01_research_question.ipynb` notebook and tracking files.
