# Task 1 — AI Output

- **Name:**
- **AI tool and model:** (e.g., Gemini 2.5 Flash, ChatGPT GPT-5, Copilot)
- **Date and time prompted:**
- **Data provenance:** (copy the provenance note from `baseline_summary.md`)
- **Columns I removed before prompting (privacy):**

## Prompt I used (copy it exactly)

```text
(paste your full prompt here)
```
````markdown
ROLE: You are Senior data analyst.

CONTEXT: The data below is [data on 24 community technology workshop series classes; use the
provenance note in baseline_summary.md]. Personal information has been removed.

TASK: Write a summary of this dataset for [A planning and design growth team] in [120-180 words using power words].

INCLUDE: [risks and limitations from this data set and rating ]

RULES: [use only numbers and rating based on the numbers given"]

FORMAT: paragraph format

DATA:

```
workshop_id	date	neighborhood	topic	time_slot	registered	attended	avg_rating followup_signups		
W01	3/3/2026	Englewood	Online Job Search	Weekday 10am	22	12	4.7	5		
W02	3/5/2026	Rogers Park	Online Job Search	Weekday 6pm	18	15	4.4	6		
W03	3/7/2026	Logan Square	Intro to Spreadsheets	Saturday 11am	19	17	4.2	4		
W04	3/12/2026	Englewood	Smartphone Essentials	Weekday 6pm	27	21	4.5	3		
W05	3/14/2026	Pilsen	Online Job Search	Saturday 11am	24	21	4.6	8		
W06	3/18/2026	Pilsen	Online Safety Basics	Weekday 6pm	23	18	4.5	3		
W07	3/21/2026	Bronzeville	Smartphone Essentials	Saturday 11am	24	20	4.4	3		
W08	3/25/2026	Logan Square	Online Job Search	Weekday 6pm	23	19	4.7	7		
W09	4/1/2026	Bronzeville	Intro to Spreadsheets	Weekday 6pm	16	13	4.4	3		
W10	4/4/2026	Rogers Park	Smartphone Essentials	Saturday 11am	24	21	4.3	4		
W11	4/7/2026	Logan Square	Smartphone Essentials	Weekday 6pm	24	18	4.3	4		
W12	4/11/2026	Austin	Intro to Spreadsheets	Saturday 11am	19	16	4	3		
W13	4/14/2026	Pilsen	Smartphone Essentials	Weekday 10am	20	11	4.6	2		
W14	4/16/2026	Bronzeville	Online Safety Basics	Weekday 10am	21	12	4.6	2		
W15	4/23/2026	Pilsen	Intro to Spreadsheets	Weekday 6pm	24	19	3.9	4		
W16	4/25/2026	Rogers Park	Intro to Spreadsheets	Saturday 11am	16	14	4.3	2		
W17	4/30/2026	Austin	Online Safety Basics	Weekday 10am	17	9	4.4	1		
W18	5/2/2026	Logan Square	Online Safety Basics	Saturday 11am	20	18	4.6	4		
W19	5/6/2026	Englewood	Intro to Spreadsheets	Weekday 10am	23	13	4	2		
W20	5/13/2026	Austin	Online Job Search	Weekday 6pm	27	21	4.6	8		
W21	5/16/2026	Bronzeville	Online Job Search	Saturday 11am	23	19	4.9	7		
W22	5/19/2026	Austin	Smartphone Essentials	Weekday 10am	25	14	4.4	2		
W23	5/23/2026	Englewood	Online Safety Basics	Saturday 11am	21	18	4.6	3		
W24	5/26/2026	Rogers Park	Online Safety Basics	Weekday 6pm	18	15	4.3	3		


````


```markdown
**Data provenance:** `ai/workshops_spring2026.csv` is a synthetic dataset created for i.c.stars Tech Foundations Performance Assessment C (Week 9), November 2026. The "Neighborhood Tech Hub," its workshops, and every name and email address in the file are fictional
```
## AI output (copy it exactly; do not fix anything here)
Across 24 workshops (March 3 to May 26, 2026), 518 people registered and 394 attended. That is a solid 76% show rate, and it produced 93 follow-up signups and a strong 4.43 average rating. Online Job Search is the clear powerhouse: it drove 41 of 93 follow-ups and earned the top average rating (4.65), peaking at 4.9 in Bronzeville. Saturday 11am sessions delivered the strongest turnout (86%), while weekday 10am sessions lagged badly at 55%. Intro to Spreadsheets trailed with a 4.13 average and the lowest single score (3.9). Englewood (69%) and Austin (68%) posted the weakest attendance, a critical gap worth investigating. The limitations are serious. Above all, this is a synthetic dataset built for an i.c.stars assessment, so it can sharpen planning methods but must not drive real program decisions. Each neighborhood hosted only four sessions, so comparisons rest on thin samples. Ratings are averages without response counts, reflect attendees only, and cluster tightly between 3.9 and 4.9. Follow-up signups measure interest, not completed outcomes.
(paste the AI's full response here)
