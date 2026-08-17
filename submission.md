# Project Submission Report

## 1. Student Details

- **Full Name:** Anab Kassim Bishar
- **GitHub Username:** kbAnab
- **Email:** kassim.anab@strathmore.edu

---

## 2. Deployed Project Link

- **Live GitHub Pages URL:** https://is-project-2026.github.io/dictionary-167683/

---

## 3. Reflection — Grounded in Your Git History


### A. Your Best Commit

- **Commit URL:** (https://github.com/IS-PROJECT-2026/dictionary-167683/commit/98cbfcad4cf5d4f04796289a62ea78709a5871d9)
- **Why this one?** I was able to use good practices for commits and fix a problem from the previous commit

### B. A Mistake or Struggle 

- **Link to the evidence:** (https://github.com/IS-PROJECT-2026/dictionary-167683/commit/e552a2a42809c7074427a812d7dfda289442b2c8)
- **What happened and how did you recover?** I accidentally made a branch into the main branch without first having a main branch. I later had to create a main branch and switch it to default.

### C. A Pull Request You're Proud Of

- **PR URL:** https://github.com/IS-PROJECT-2026/dictionary-167683/commit/b2470c89457e95a1d5565a26c10f38bda8ddb259
- **What did you check before merging?** I checked to ensure it would simulate the error.

### D. One Thing You Would Do Differently

- **What would you change?** I would have a better plan and clear steps to follow before starting the issue. It made me accidentally not create a main branch at the beginning.
- **Link to the evidence of the original decision:** (https://github.com/IS-PROJECT-2026/dictionary-167683/commit/e552a2a42809c7074427a812d7dfda289442b2c8)

---

## 4. Screenshots of Key GitHub Features

Demonstrate your workflow mechanics by embedding your screenshots below.

### A. Milestones and Issues

<img width="317" height="167" alt="Screenshot 2026-08-17 215720" src="https://github.com/user-attachments/assets/47e7cd45-66b6-4770-8aa2-d7aad8a27b02" />

<img width="331" height="153" alt="image" src="https://github.com/user-attachments/assets/9d68c950-4fb2-4b2f-97ad-ecc9ad1fd842" />

* **Caption:** I chose three milestones which are uploading the code into the repository, testing to see if it can be deployed on github and reviewing everything after. The issues correspond to the milestones and are closed.

### B. Project Board

<img width="449" height="171" alt="Screenshot 2026-08-17 215816" src="https://github.com/user-attachments/assets/c3691f95-5d68-4c98-98b4-214e7b0341ca" />

* **Caption:** The different issues entered various states such as Todo, in progress and done. The states change as an issue is resolved.

### C. Branching Architecture

<img width="460" height="239" alt="Screenshot 2026-08-17 215915" src="https://github.com/user-attachments/assets/6a9c0c20-9f6c-4161-a307-e806a7e1c90f" />

* **Caption:** [The different branches are shown with the branch main being the default branch  that cannot be committed to directly.]

### D. Pull Requests & Traceability
<img width="397" height="239" alt="Screenshot 2026-08-17 220146" src="https://github.com/user-attachments/assets/104bd526-3ce3-4789-b118-65a07b3877c5" />

 **Caption:** A pull request regarding changes made to the main css file for the index page. It has been merged.


## 5. Merge Conflict Evidence


**What cause did you use?** Changing the same line on two branches.

<img width="589" height="56" alt="image" src="https://github.com/user-attachments/assets/785e8bbd-e134-4c07-9fd0-083ce6c65101" />

Branch `conflict/branch-B` attempted to merge `conflict/branch-A`. Both branches modified the same heading line in `index.html` differently, so Git could not automatically determine which version should be retained.

<img width="722" height="152" alt="conflict_evidence png" src="https://github.com/user-attachments/assets/e1898258-e9a3-4571-b7e3-500ccf11788c" />

**Caption:** Git identified two competing versions of the same section of `index.html`. I reviewed both changes and selected the appropriate final heading before removing the conflict markers.


<img width="365" height="60" alt="Screenshot 2026-08-17 222333" src="https://github.com/user-attachments/assets/b547cbea-3499-4736-b6c9-fa4e2b17fcc3" />

**Caption:** The conflict was resolved manually, the resulting file was staged, and the merge was committed. The final Git history shows the conflict resolution commit and no remaining unresolved merge state.

