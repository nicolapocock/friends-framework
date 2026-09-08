# the friends framework

a marketing team of six ai agents and one operator. one job each, one operator
moving work between them.

this repo is the framework as files you can lift — plus the full
[16-page guide](the-friends-framework.pdf) as a pdf.

---

## the idea

one agent = one job. never a "do everything" agent — they get vague and go wrong.
the specialists never talk to each other directly; an operator routes every
hand-off. it's a team with a floor manager, not a group chat.

six named roles you already understand, so the system is easy to hold in your head:

| agent | function | owns |
|---|---|---|
| **ross** | research | who to target, what's moving, what competitors shipped |
| **phoebe** | strategy | the angle, the positioning, the brief everyone builds from |
| **chandler** | copy | every word that ships, plus the voice pass |
| **rachel** | design | visual identity and every asset that carries it |
| **joey** | outreach | cold approach, follow-up, proposals, warm-up video |
| **monica** | ops + dms | sending, scheduling, dms, qa, compliance |
| **hermes** | the operator | routes hand-offs, runs the schedule, one brief a day |

full role definitions in [`agents/`](agents/).

---

## the three-file spine

every agent loads the same three things before it touches a task:

1. **[`rules.md`](templates/rules.md)** — what it must never do. shared by every agent.
2. **[`context.md`](templates/context.md)** — who you are, who you serve, what you sell. shared by every agent.
3. **the task skill** — the how-to for this one job. one per agent (see [`agents/`](agents/)).

rules and context are shared. the task skill is the specialism. that's the whole pattern.

---

## the hand-offs

every arrow runs through hermes. the agents never hand to each other directly.

- **content** — ross to phoebe to chandler + rachel to monica (schedules & sends)
- **leads** — ross to chandler + rachel to joey to monica (books & follows up)
- **inbound** — monica triages every dm, real enquiries go to joey, the rest get logged

draw this on paper before you build anything. if you can't draw the arrows, the
roles aren't clear enough yet.

---

## build order

don't build six. build one.

1. **start with the job that's most on fire** — usually chandler (writing) or ross
   (research). build it alone, with its three files. run it two weeks.
2. **add a second, and a written hand-off** — the hand-off spec matters more than
   either agent.
3. **at three agents, add hermes** — three is where manual routing breaks.
4. **add the rest only when the last one is boring** — a finished agent is predictable.

most people need three. six is a full agency. build to your actual workload.

---

## five ways it goes wrong

- **agent sprawl** — one agent per passing idea. cap the count, merge overlaps.
- **no rules file** — governance written after the incident is too late.
- **agents talking to each other** — a failure in one cascades and you can't trace it.
- **no human gate** — a person approves anything with your name or face on it.
- **one model for everything** — match the model to the job.

none of these are ai problems. they're org-design problems.

---

## start here

1. name the job costing you the most hours. just that one.
2. copy [`templates/agent-role.md`](templates/agent-role.md) and fill it in. one page, plain language.
3. build it with `rules.md` + `context.md` + its task skill. run it two weeks before adding a second.

that's the whole method. one agent, three files, a human gate. the team comes
later — or never, if one is enough.

---

made by [@getgitgirl](https://instagram.com/getgitgirl) · [getgitgirl.framer.ai](https://getgitgirl.framer.ai) · built with claude, obviously
