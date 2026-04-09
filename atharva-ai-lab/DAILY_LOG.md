# Daily Build Log

A running log of what I did each day. One entry per day, newest at the top.


<!-- TEMPLATE (copy this for each new entry):
---
## YYYY-MM-DD — [One line title of what you did]

**Area:** stock-tools / devapixels / openclaw / work-tools / experiments

**What I did:**
[2–3 sentences. What did you build, learn, or ship? Be specific.]

**File(s) committed:**
- `path/to/file.md`

**Time spent:** ~X min

**What I'd do differently / next step:**
[One line]

**Learnings:**
[One line]

-->
## 2026-04-09 — Built phase 2,3,4,5, and 6 partially

**Area:**  work-tools / experiments

**What I did:**
Executed everything from phase 2 to phase 6 partially. The backend was deployed on railway but the frontend couldn't be deployed as there was a blocker with the vercel account. Vercel had raised 3 pending invoices without any usage. This is pending with Vercel Support team - and they plan to cancel the previously raised invoices - waiting for them to revert back to complete the full phase wise development. 

**File(s) committed:**
....

**Time spent:** ~2-3 hrs

**What I'd do differently / next step:**
Things have been on track so far, next step is for me to test the product understand my interaction patterns and fix the remaining gaps as well.
Luckily I didn't face any major hallucination issues. The speed of development on this day primarily increased because of additional 20$ credit usage provided for free by Anthropic.

**Learnings:**
After completeting all the 6 phases, I have figured that it is a good working approach - to create an extremely detasiled PRD and system architecture document using Claude. But instead of executing all at once - again using claude to split it into micro-features, and then executing each of the micro-features in phased manner - while testi ng each microfeature in each phase is a good approach. This leads to better adhearance to the prompts and the plan.

---
## 2026-04-08 — Built Phase 0, 1a, 1b of the KRD Tool.

**Area:** work-tools / experiments

**What I did:**
Executed each of the following phases and built a working KRD generation tool which is able to generate each of the KRD sections, and the LLM response streams to me word by word vs all of it being shared all at once after a 60s wait.

**File(s) committed:**
....

**Time spent:** ~1.5 hrs

**What I'd do differently / next step:**
Next step is to execute the remaining phases 2,3,4,5 and 6. Meanwhile I will also spend some time using the product to indentify some quick fixes as well.

---


## 2026-04-07 — Phase wise plan to build a tool reduce KRD writing time from 1.5hr to 20mins.

**Area:** work-tools / experiments

**What I did:**
Brainstormed with Claude on what should be scope of the build.
Generated the PRD for each individual phase of the development.
This includes the complete CI/CD pipeline, git versionining setup. Monolith architecture with clean frontend and backend isolation.

**File(s) committed:**
No commits yet

**Time spent:** ~40 mins

**What I'd do differently / next step:**
Next step is to set up the environment and execute each phase using claude code.


---

## 2025-04-06 — Repo setup

**Area:** experiments

**What I did:**
Set up atharva-ai-lab — folder structure, README, templates, daily log. First commit of the build-in-public journey.

**File(s) committed:**
- `README.md`
- `DAILY_LOG.md`
- `templates/`

**Time spent:** ~30 min

**Next step:**
First real experiment tomorrow — pick one thing from any area and commit something useful.

---
