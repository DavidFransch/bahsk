# Decisions

Every significant choice gets added to the bottom of this file, with the date and the reason.
Do not edit or delete old entries. If a decision changes, add a new entry that says so.

The first four entries were made before this repo existed. They are dated the day they were written down.

---

## 2026-10-04 — V1 is the enquiry layer

V1 handles guest enquiries: reading them, drafting replies and checking availability.
It does not replace the lodge's booking system.
**Reason:** most lodges already run a property management system. The enquiry inbox is where they lose the most time. *(Reason drafted at setup — please confirm or correct.)*

## 2026-10-04 — One product with two setup modes

We build one product with a setup mode (`layer` or `full`), not two separate prototypes.
**Reason:** the screens overlap heavily. One prototype keeps the design consistent and is half the work to maintain. *(Reason drafted at setup — please confirm or correct.)*

## 2026-10-04 — Availability is read-only on ResRequest and NightsBridge

We read availability from both systems. We do not write to either.
**Reason:** the access we have on both systems is read-only.

## 2026-10-04 — No automated holds in V1

The product will not create provisional holds by itself in V1.
**Reason:** with read-only access we cannot place holds, and the team should stay in control of inventory. *(Reason drafted at setup — please confirm or correct.)*
