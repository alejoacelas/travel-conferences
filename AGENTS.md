---
agent_context:
  version: 1
  groups: []
  visibility: public
---
<!-- agent-context:begin sha256=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->
<!-- agent-context:end -->

# Conferences

See [README.md](README.md) and [calendar.md](calendar.md).

At the start of conference work, ask whether Alejo wants the repository list synchronized
with Google Calendar. If yes:

1. Check the official source before trusting a stored date.
2. Read the relevant bounded calendar window and identify the target calendar before any
   write.
3. Show missing, changed, duplicate, and cancelled events. Do not infer a city, time zone,
   or date from previous years.
4. Add only confirmed events. Put the official URL and this folder’s path in the event
   description; preserve existing attendee, reminder, and recurrence data when updating.
5. Verify the calendar after writes and update the checked date in this folder.

For EAG, EAGx, and EA Summits, treat the [official upcoming-conferences page](https://www.effectivealtruism.org/ea-global/events)
as the canonical index. Track each event separately; do not create one recurring series.

Keep unresolved names and likely annual retreats in `camps.md` with brackets around the
missing fact. Update `reproduce/README.md` whenever the source list or sync method changes.

See [README.md](README.md) and [AGENTS.md](AGENTS.md). Before changing the event list, ask
whether to compare it with Google Calendar; do not write calendar events until the target
calendar and exact official dates are known.
