# Deliverable 7 — Certificate System
## COHORT-ZERO-0

---

## A. Certificate Design Specification

The Zidni Academy AI Skills Certificate will be a simple digital document that can be:
- Generated as a PDF
- Sent via WhatsApp as an image
- Printed on A4 paper
- Shared on Facebook / LinkedIn

### Layout (A4 Portrait)

```
┌─────────────────────────────────────┐
│                                     │
│           زدني أكاديمي               │
│         ZIDNI ACADEMY               │
│                                     │
│    شهادة إتمام                      │
│    Certificate of Completion        │
│                                     │
│    هذه الشهادة تثبت أن               │
│    This certifies that              │
│                                     │
│       [STUDENT NAME]                │
│          (بخط كبير)                  │
│                                     │
│    قد أكمل بنجاح                     │
│    has successfully completed       │
│                                     │
│    تحدي 7 أيام في الذكاء الاصطناعي   │
│    7-Day AI Challenge               │
│                                     │
│    من زدني أكاديمي — نواذيبو         │
│    Zidni Academy — Nouadhibou       │
│                                     │
│    التاريخ: [DATE]                   │
│                                     │
│    ───────                          │
│    محي الدين الشيخ                  │
│    مؤسس زدني أكاديمي                │
│    Founder, Zidni Academy           │
│                                     │
│    [QR Code: link to verification]  │
│                                     │
│    الموارد الطبيعية قد تنتهي،        │
│    لكن المعرفة لا تنتهي.             │
│    Natural resources may end,       │
│    but knowledge grows when shared. │
│                                     │
└─────────────────────────────────────┘
```

### Technical Specification

| Element | Specification |
|---|---|
| Size | A4 (210 x 297 mm) |
| Orientation | Portrait |
| Background | White / cream with subtle border |
| Color scheme | Dark navy (#0f3460) for headers, red accent (#e94560) for brand elements |
| Font (Arabic) | Arabic Typesetting or Traditional Arabic |
| Font (English) | Segoe UI or Arial |
| Student name | 24pt bold, centered |
| Quality | 300 DPI minimum for print |
| Format | PDF (for print/email) + PNG (for WhatsApp) |

### How to Create (No Design Software Required)

**Option 1: Google Docs (Recommended — fastest)**
1. Open Google Docs
2. Set page size to A4
3. Type the Arabic text with the layout above
4. Add a thin border (Insert > Drawing > Rectangle)
5. Export as PDF
6. Save the Google Doc as a template — reuse for each student

**Option 2: Canva (Free)**
1. Search template "Certificate Arabic" or "Certificate simple"
2. Customise colours to #0f3460 + #e94560
3. Add student name as editable text
4. Download as PDF

**Option 3: Microsoft Word**
1. New document > Search "Certificate" template
2. Adjust layout to match above
3. Save as PDF

---

## B. Graduation Requirements

To graduate from the 7-Day Challenge and receive the certificate:

| # | Requirement | Verification Method |
|---|---|---|
| 1 | Register with real name and phone | Google Sheet entry |
| 2 | Complete Day 1 activity (ChatGPT account + 5 questions) | Send "تم" + screenshot in group |
| 3 | Complete Day 2 activity (3 strong prompts) | Send "تم" + sample prompt |
| 4 | Complete Day 4 activity (Facebook post) | Send "تم" + screenshot of post |
| 5 | Complete Day 7 activity (Personal AI toolkit) | Send "تم" + personal assistant prompt |
| 6 | Complete at least 5 of 7 days total | Tracking sheet: Day X Done = YES for ≥5 days |
| 7 | Must include both Day 1 AND Day 7 | Minimum core requirements |

**Minimum active days to graduate: 5 of 7**

**Minimum screenshots provided: 2** (Day 1 account creation + one additional day of the student's choice)

---

## C. Completion Verification Process

### Step-by-Step Workflow

```
Day 7 ends
    │
    ▼
Founder opens tracking sheet
    │
    ▼
Filter for students with ≥5 "Done" = YES
    │
    ▼
For each qualifying student:
  1. Verify Day 1 and Day 7 are both YES
  2. Check at least 2 screenshots exist
  3. Confirm the student's name and profession are correct
    │
    ▼
Mark Graduated = YES in tracking sheet
    │
    ▼
Generate certificate:
  - Copy certificate template
  - Replace [STUDENT NAME]
  - Replace [DATE]
  - Export/Save as PDF
    │
    ▼
Send certificate to student via WhatsApp DM:

  "🎓 مبروك [NAME]! 
   شهادة إتمام تحدي 7 أيام في الذكاء الاصطناعي جاهزة.
   [attached certificate PDF]
   فخور بك. استمر في التعلم! 🚀"
    │
    ▼
Mark Certificate Sent = YES in tracking sheet
    │
    ▼
Save a copy in:
  evidence/COHORT-ZERO-0/certificates/[STUDENT_NAME].pdf
```

### 48-Hour Delivery Target

The gate requires certificates within 48 hours of Day 7 completion. Given Cohort Zero expects 10-20 graduates, the Founder should:

1. **Day 7 evening:** Quick scan of tracking sheet — identify graduates
2. **Day 8 morning:** Generate all certificates (batch — 30 minutes max)
3. **Day 8 evening:** Send all certificates via WhatsApp DM
4. **Day 9 (if needed):** Follow up with anyone missed

---

## D. Certificate Verification System

Since Cohort Zero has no website or database, verification is handled via WhatsApp:

**Verification process:**
1. Third party contacts Founder: "هل [NAME] حصل على شهادة من زدني أكاديمي؟"
2. Founder checks tracking sheet for the student name
3. Founder confirms: "نعم، [NAME] أكمل تحدي 7 أيام في [DATE]. هذه شهادة صحيحة."

**For future scale:** A QR code on the certificate linking to a simple verification page can be added when a website exists.