# Deliverable 5 — Attendance Tracking System
## COHORT-ZERO-0

---

## Google Sheet Structure

Create a Google Sheet named: **"Cohort Zero — Zidni Academy Tracker"**

### Sheet 1: Master Roster

Columns (A through Z):

| Column | Header | Type | Description |
|---|---|---|---|
| A | Student ID | Text | C001, C002, ... C030 |
| B | Full Name | Text | As provided during registration |
| C | Phone | Text | Mauritania number (+222 format) |
| D | Profession | Text | Teacher, Trader, Student, etc. |
| E | Neighborhood | Text | Which area of Nouadhibou |
| F | Paid (500 MRU) | YES/NO | Payment confirmed |
| G | Payment Date | Date | When payment was received |
| H | Day 1 Done | YES/NO | "تم" received |
| I | Day 1 Note | Text | Screenshot or comment |
| J | Day 2 Done | YES/NO | |
| K | Day 2 Note | Text | |
| L | Day 3 Done | YES/NO | |
| M | Day 3 Note | Text | |
| N | Day 4 Done | YES/NO | |
| O | Day 4 Note | Text | |
| P | Day 5 Done | YES/NO | |
| Q | Day 5 Note | Text | |
| R | Day 6 Done | YES/NO | |
| S | Day 6 Note | Text | |
| T | Day 7 Done | YES/NO | |
| U | Day 7 Note | Text | |
| V | Engagement Score | 1-5 | 1=low, 5=high (subjective) |
| W | Graduated | YES/NO | Completed 5+ of 7 days |
| X | Certificate Sent | YES/NO | Certificate PDF delivered |
| Y | Testimonial Collected | YES/NO | Written/voice/video received |
| Z | Converted to 28-Day | YES/NO | Enrolled in full program |
| AA | Notes | Text | Free text |

### Sheet 2: Daily Summary

| Column | Header | Description |
|---|---|---|
| A | Day | 1 through 7 |
| B | Date | Date of the day |
| C | Total Members | Group size at start of day |
| D | Sent "تم" | Number who completed task |
| E | Shared Screenshot | Number who provided visual proof |
| F | Asked Questions | Number who participated in discussion |
| G | Drop-off Rate | % who didn't complete |
| H | Cumulative Completion | Total unique completers so far |

### Sheet 3: Revenue

| Column | Header | Description |
|---|---|---|
| A | Student Name | |
| B | Amount Paid (MRU) | |
| C | Payment Method | Orange Money / Cash / Bank |
| D | Date | |
| E | Receipt Sent | YES/NO |
| F | Notes | |

---

## How to Use (Manual Process — No Automation)

### Daily Workflow for Founder:

1. **Morning (8 AM):** Copy today's task message from the challenge structure doc. Paste into WhatsApp group.

2. **Throughout the day:** As students send "تم" + screenshots:
   - Open the Google Sheet
   - Find the student's row
   - Mark Day X Done = YES
   - Paste any note/screenshot reference in the Notes column

3. **Evening (8 PM):**
   - Check which students did NOT send "تم"
   - Send a gentle reminder in group (not individual DMs)
   - Update the Daily Summary sheet

4. **Daily summary calculation:**
   - Count YES in today's column → that's your daily active count
   - Compare to previous day → that's your retention rate

---

## CSV File

A companion CSV file is at:

`cohort-zero/tracking/cohort-zero-tracker.csv`

Contains 30 pre-filled student rows (C001-C030) with all columns ready. Founder can:
- Import into Google Sheets
- Or use Excel/LibreOffice
- Or print and fill manually

---

## Metrics to Track Daily

| Metric | Day 1 | Day 2 | Day 3 | Day 4 | Day 5 | Day 6 | Day 7 |
|---|---|---|---|---|---|---|---|
| Group size | | | | | | | |
| Task completions | | | | | | | |
| Screenshots shared | | | | | | | |
| Questions asked | | | | | | | |
| Drop-off rate | | | | | | | |
| Cumulative unique | | | | | | | |

---

## Graduation Status Calculation

**Graduated = YES** if student completed 5+ of 7 days AND sent "تم" for at least Day 1 and Day 7.

**Why Day 1 + Day 7 required:** Day 1 establishes the account. Day 7 builds the personal toolkit. Both are essential for the certificate claim of "can use AI independently."
