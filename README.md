# PICU Pre-Procedure Checklist

A bedside pre-procedure checklist for Washington University Pediatric Critical Care fellows and
supervising faculty. Six procedures: intubation, central venous line, chest tube, arterial line,
lumbar puncture, and natural airway sedation.

**Open it:** https://neelshah4.github.io/picu-pre-procedure-checklist/

Built for a phone, held one-handed, at the bedside. It works offline once loaded and makes no
network request of any kind after the page loads. Two links leave the page if you tap them: the
feedback form, and a positioning reference on the intubation checklist.

## It stores nothing

No field on the page accepts a patient identifier, and nothing stores one. No
local storage, no session storage, no cookies, no analytics, no server. Ticks clear when you
leave a procedure and when you start a new patient. Exactly two outbound links exist: the
fellowship's own feedback form, and, on the intubation positioning row, a pediatric-anaesthesia
handbook page. A link out is not a data path. Nothing about a patient leaves this page, because
nothing about a patient is ever on it.

## What is on it

The 88 checklist items come verbatim from the division's *Pre-Procedure Checklists* document,
wording unchanged.

Everything else on the page came from published evidence and carries no institutional authority:
the pause structure, the time-out and huddle rows, the attempt limits, the laterality,
sterile-barrier, coagulation and confirmation rows, the emergency bypass cards, and every
reference table inside a Note. As of round 3 these are **no longer marked row by row** — the
per-row dashed box and "Added" tag were removed at the author's direction. The distinction is
stated once, in the About block under *Where the lines come from*.

Each procedure opens with the division's **procedural supervision policy, quoted verbatim**.
Nothing on the page is computed from fellow year; the policy's own words decide. The stored
source for that text is in `_work/SOURCE-SUPERVISION-POLICY.md`.

Each procedure ends with a link and a QR code to the **PICU Fellow Brief Feedback Form**. The
safety pause is unscored and separate from that form, so that a pause never feeds an
assessment.

## Structure

Items are grouped into at most three pause points, none longer than seven items, then a fourth
**After** block carrying the post-procedure huddle as a single row. The checklist literature puts
the ceiling at fewer than ten items *per pause point*, and the WHO surgical checklist clears it
the same way, by splitting 19 items across three phases.

Pre-huddle box counts: intubation 20, central venous line 21, chest tube 16, arterial line 17,
lumbar puncture 14, natural airway sedation 19.

Intubation, central venous line and chest tube carry a bypass card at the top: if the child is
arresting, do the procedure, say patient / procedure / side aloud, and come back for the huddle.
Arterial line, lumbar puncture and natural airway sedation do not, at the author's direction.

## Printing

Open a procedure and print it — you get that procedure with every note expanded, not all six.
The collapsed notes are opened automatically before printing and restored afterwards.

## Provenance and limits

Every PMID on the page was resolved against PubMed, and every printed dose, size and band was
checked against the source that carries it: a PubMed record, a full text, an FDA label on
DailyMed, or a manufacturer's own catalogue. Age-banded hypotension cut-points are still left
out, because no source was resolved, and so is any ETT depth-at-the-lip formula. Use the unit's
own reference card for those.

Some things were asked for and deliberately not shipped, because no source could be resolved for
them: laryngoscope blade sizes, oral and nasopharyngeal airway sizes, any chest-tube French size
by weight or age, and any shock-adjusted induction dose.

Rocuronium 1–1.5 mg/kg and ketamine 1 mg/kg are the **unit's** doses for intubation, given on the
author's authority. The manufacturers' labels give different numbers, and those numbers were
removed from the page in round 3 so that two figures never sit side by side. Atropine 0.02 mg/kg
with no minimum and a 0.5 mg ceiling is also the unit's figure. Etomidate and fentanyl remain the
label figures.

This is a teaching and prompting aid for licensed clinicians. The division's policy documents
govern wherever they and this page differ.

Maintained by Neel Shah, MD. Licensed CC BY-NC 4.0.
