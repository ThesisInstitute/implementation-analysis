# Implementation analysis

An experiment in AI-assisted legislative implementation analysis — the
qualitative sibling to [Thesis](https://app.thesisinstitute.org)'s scored
forecasting. Where Thesis asks *"what number will this produce?"*, this asks
*"can this be implemented as written, and what will that do to the number?"*

Today that analysis barely exists as a public function. Scorekeepers
estimate budget effects; support agencies describe law; nobody
systematically tells a drafter *this carve-out will add administrative
burden to the actors you need, and take-up will die* — that critique lives
almost entirely with lobbyists, who only make it for their own clients.

## The flow

Given bill text, the analyst produces:

1. **Imputed goals** `[CONFIRM]` — what the drafters appear to be trying to
   achieve, stated for the member's staff to confirm or amend before full
   analysis.
2. **Likely effects** `[TOLD REGARDLESS]` — downstream consequences,
   including adversarial ones, surfaced whether or not they serve the
   stated goals.
3. **Implementation barriers** — provision-level: which actor bears new
   burden, what breaks at scale, where statutory specificity will age
   badly.
4. **Outcome metrics** — officially published, first-print-resolvable
   series suitable for pre-registered conditional forecasts (the bridge
   back into Thesis: "P(metric path | enactment vs not)").

## Case studies

`case-studies/` holds the training corpus: real provisions whose
implementation story is known. Each follows `TEMPLATE.md`. The corpus is
the heart of this project — the analysis is only as good as the examples
of how drafting choices played out in practice.

## Using this with Claude Code

Open this repo in Claude Code and point it at a bill:

    Read ANALYZE.md, then apply it to <bill text file or URL>,
    grounding your implementation-barrier reasoning in case-studies/.

Add every new worked example back into `case-studies/` — the corpus
compounds.

## Status

Prototype (July 2026). First live test: the Farm Bill 2.0 discussion draft
(Agricultural Act of 2026), Titles II and VI — see `demos/` when it lands.
Apache-2.0.
