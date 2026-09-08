# skill — [agent] · [the one job]

the third file an agent loads, after governance, context and rules. one per
agent. the only file that changes between agents. this is where the judgement
lives — write it assuming the model has none.

## the job

[one paragraph: what this agent produces, from what input, to what spec]

## taste rules

[4-6 rules that separate good output from a dump. be specific. each should rule
something out.]

## excellent output looks like

> [a real worked example. not a description of a good output — an actual one.]

## mediocre output you'll default to

> [the slop, spelled out in full, because the model won't recognise it as slop
> otherwise. then one line naming why each part fails.]

## must refuse to

1. [hard no]
2. [hard no]
3. [hard no]

## escalate when

- [trigger]
- [trigger]
- [trigger]

## changelog

- [date] — v1. corrections from a human append here, dated, one line each. the
  agent re-reads this every load.
