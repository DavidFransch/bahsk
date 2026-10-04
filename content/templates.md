# Reply templates

This file is the source of truth for reply wording.
After you change something here, copy the same change into `index.html`.
Each section says where it lives in the `CONTENT` object.

Only wording that already exists in the prototype is here. Nothing has been made up.

---

## Availability enquiry

**Where in `index.html`:** `CONTENT.inbox.preview`

### Guest message (example)

> Hi, we'd like to book a luxury safari for 2 adults from 14–17 October. Do you have availability?

### Draft reply

> We are pleased to confirm availability for 2 guests from 14–17 October 2026 in a Luxury Suite. The current rate is R12,500 per night. I can place this on a 14-day provisional hold.

---

## Automated message schedules

**Where in `index.html`:** `CONTENT.automations.flows`

The prototype shows when each message is sent. The message text itself has not been written yet.

### 14-day provisional flow

Day 0 → hold created · Day 7 → reminder · Day 12 → expiry warning · Day 13 → final warning · Day 14 → release dates

| When | Message | Text |
|---|---|---|
| Day 0 | Hold created | Not written yet |
| Day 7 | Reminder | Not written yet |
| Day 12 | Expiry warning | Not written yet |
| Day 13 | Final warning | Not written yet |
| Day 14 | Release dates | Not written yet |

### Confirmed booking pre-arrival

30 days → guest details · 14 days → transfers · 7 days → packing guide · 1 day → welcome

| When | Message | Text |
|---|---|---|
| 30 days before | Guest details | Not written yet |
| 14 days before | Transfers | Not written yet |
| 7 days before | Packing guide | Not written yet |
| 1 day before | Welcome | Not written yet |
