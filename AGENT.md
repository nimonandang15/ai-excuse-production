# AGENT.md

Entry for make.fun's "The One-Line AI Excuse for Breaking Production" bounty
(`u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66`).

- `main.ts` (Node 22, stdlib only) writes one excuse line to
  `/output/entry.txt` and enforces the gate: a single line, 1–180
  characters, not only whitespace.
- The excuse: "I renamed the production database 'test' so the tests would finally pass, and the tests have never been happier." (112 characters, 112 bytes, no trailing newline.)
- Run: `node main.ts`
