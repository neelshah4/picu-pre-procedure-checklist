# PICU Pre-Procedure Checklist

A bedside pre-procedure checklist for Washington University Pediatric Critical Care fellows and
supervising faculty. Six procedures: intubation, central venous line, chest tube, arterial line,
lumbar puncture, and natural airway sedation.

**Open it:** https://neelshah4.github.io/picu-pre-procedure-checklist/

Built for a phone, held one-handed, at the bedside. It works offline once loaded and makes no
network request of any kind after the page loads.

## It stores nothing

No field on the page accepts a patient identifier, and nothing stores one. No
local storage, no session storage, no cookies, no analytics, no server. Ticks clear when you
leave a procedure and when you start a new patient. The only outbound link is the fellowship's
own feedback form.

## What is on it

The 88 checklist items come verbatim from the division's *Pre-Procedure Checklists* document.
Those are shown as solid-bordered rows with no tag.

Rows marked **Added** are not division policy. They come from the published evidence and are
offered, not mandated; each carries a note with its reason and its source. The distinction is
stated in the legend on the home screen, because a fellow needs to know at a glance which lines
are the institution speaking and which are the literature.

Each procedure opens with the division's **procedural supervision policy, quoted verbatim**.
Nothing on the page is computed from fellow year; the policy's own words decide. The stored
source for that text is in `_work/SOURCE-SUPERVISION-POLICY.md`.

Each procedure ends with a link and a QR code to the **PICU Fellow Brief Feedback Form**. The
safety pause is deliberately unscored and separate from that form: a pause that feeds an
assessment invites a fellow to perform confidence and hide the concern the pause exists to
surface.

## Structure

Items are grouped into at most three pause points of about seven items each, then a fourth
**After** block for the post-procedure huddle. That shape is not arbitrary. The checklist
literature puts the ceiling at fewer than ten items *per pause point*, and the WHO surgical
checklist clears it the same way, by splitting 19 items across three phases.

Every procedure also carries a bypass card at the top: if the child is arresting, do the
procedure, say patient / procedure / side aloud, and come back for the huddle.

## Printing

Open a procedure and print it — you get that procedure with every note expanded, not all six.
The collapsed notes are opened automatically before printing and restored afterwards.

## Provenance and limits

Every PMID on the page was resolved against PubMed during the build, and every printed number
was checked against its abstract. Two things were deliberately left out because no source was
resolved: age-banded hypotension cut-points and ETT size or depth formulas. Use the unit's own
reference card for those.

This is a teaching and prompting aid for licensed clinicians. It is not a protocol, not an order
set, and not a substitute for the division's policy documents.

Maintained by Neel Shah, MD. Licensed CC BY-NC 4.0.
