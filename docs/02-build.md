# Build

**Goal:** Ship the smallest artifact that tests the Find hypothesis.

## Outputs

- A usable artifact (doc, template, script, tiny app)
- README a stranger can follow
- Clear “what this is / isn’t”
- No secrets in the repo

## Steps

### 1. Shrink the bet
Ask: *What’s the smallest thing that could disprove my hypothesis?*

Examples of valid Phase-0 builds:
- A checklist people actually use
- A worked example
- A script that removes one painful step
- A template that replaces a blank page

Not required yet: multi-tenant SaaS, agent fleets, custom infra.

### 2. Choose an agentic development environment (capability)
Pick per **task**, not per identity:

- Heavy repo / PR work → whatever ADE you trust for that repo
- Research + writing → research-capable assistant
- Quick spike → fastest environment you can drive safely

Rule: **architecture defines capabilities; tools are interchangeable.**

### 3. Quality bar (minimum)
- Runs or reads cleanly without you on a call
- States limitations
- MIT (or other) license if public
- Private by default until you intentionally publish

### 4. Security bar
- No `.env`, tokens, keys, customer data
- If anything sensitive ever landed in git history, rewrite or keep private
- Rotate anything that leaked

### 5. Public by selection
Before visibility → public, ask:
- Would I show this to a hiring manager or customer?
- Does it represent the brand direction?
- Did it pass a public-repo gate?

## Anti-patterns

- Building infrastructure “for later”
- Vendor lock-in as a personality
- Shipping demos with lab passwords still in the README

## Exit criteria

A stranger can use the artifact and tell you whether the hypothesis feels true.
