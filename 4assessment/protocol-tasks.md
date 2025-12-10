**Student**: [Diana Leonova-Eliseeva, 201848735]
**Submission date**: [12/12/2025]
**Academic Year**: 2025-26

---

## Privacy & Ethics Statement

- [ ] I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names)
- [ ] I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible)
- [ ] I confirm all participants gave informed consent
- [ ] I confirm this work is my own (AI tools used for code assistance are cited below)

**AI tools used** (if any): [e.g., "Copilot for route handler boilerplate (lines 45-67 in diffs)"]

---

## 1. Protocol & Tasks

### Link to Needs-Finding (LO2)

**Week 6 Job Story #1**:
> [Paste your Week 6 job story here - the one that informed your first task]
When I have a long list of tasks and need to quickly find the ones related to a specific topic,
I want to filter the task list by keyword,
So I can immediately see the tasks that match what I'm looking for,
Because scrolling through everything is slow and I may miss important items.
**How Task 1 tests this**:
Task 1 tests the functionality and usability of the 'filter' function on the website, and directly links to the first job story by evaluating how well the filter function solves the participant's need.

---

### Evaluation Tasks (4-5 tasks)

#### Task 1 (T1): [filter tasks]

- **Scenario**: [User must find all tasks containing the word “plan”]
- **Action**: [Locate the filter/search box, type “plan”, view filtered task list]
- **Success**: [Only matching tasks remain, user can count them, metrics.csv logs T1_filter with success]
- **Target time**: [≤ 20 seconds]
- **Linked to**: [Week 6 Job Story #1]

#### Task 2 (T2): [edit task]

- **Scenario**: The task “Submit invoices” needs correcting.
- **Action**: Find and click Edit, change text to “Submit invoices by Friday”, save the change
- **Success**: Updated text appears, no validation errors, metrics.csv logs T2_edit with success
- **Target time**: ≤ 16 seconds
- **Linked to**: Week 6 Job Story #2

#### Task 3 (T3): delete task

- **Scenario**: The task “Test entry” is needs to be deleted.
- **Action**: Click Delete button, confirm deletion in dialog
- **Success**: Task disappears from list, confirmation shown (JS-on), metrics.csv logs T4_delete with success
- **Target time**: ≤ 8 seconds
- **Linked to**: Week 6 Job Story #3

#### Task 4 (T4): [add task]

- **Scenario**: A new item "Call supplier about delivery” needs to be added
- **Action**: Find the add-task input, type the task text, click submit
- **Success**: Task appears in list, no blanks or errors, metrics.csv logs T3_add with success
- **Target time**: ≤ 10 seconds
- **Linked to**: Week 6 Job Story #4

---

### Consent Script (They Read Verbatim)

**Introduction**:
"Thank you for participating in my HCI evaluation. This will take about 15 minutes. I'm testing my task management interface, not you. There are no right or wrong answers."

**Rights**:
- [ ] "Your participation is voluntary. You can stop at any time without giving a reason."
- [ ] "Your data will be anonymous. I'll use a code (like P1) instead of your name."
- [ ] "I may take screenshots and notes. I'll remove any identifying information."
- [ ] "Do you consent to participate?" [Wait for verbal yes]

**Recorded consent timestamp**: [e.g., "P1 consented 22/11/2025 14:05"]

---
