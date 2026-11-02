# Prompt Scaffold — Task 1

Fill in every `[bracket]`, then paste the finished prompt into your approved AI tool.

## Before you paste: privacy check

- Open `ai/workshops_spring2026.csv` and **delete the `host_name` and `host_email` columns** from what you paste. Names and emails are personal information (PII), even when they're fake. No PII in prompts.
- Paste the data only. Don't paste the baseline summary; the AI shouldn't see the answer you'll grade it against.

## The scaffold

```text
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


## Tips

- One clear prompt is enough. If you re-prompt, copy **every** prompt and response into `ai/ai_output.md`.
- Write down the time you start prompting and the time you get a usable answer. You'll need it for the "time saved" criterion.
