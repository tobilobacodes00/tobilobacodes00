markdown
<h3 align="center">Tobiloba Sulaimon</h3>
<p align="center"><em>Full-stack product engineer · Lagos</em></p>
<p align="center">TypeScript · Rust · Python</p>

---

A woman speaks. English for three words, Yorùbá for the next four,
and the rest somewhere neither language has a name for.
This is not an edge case. This is Tuesday.


Every major speech model hears that and returns noise. Not a worse transcript —
noise. The languages of six hundred million people, filed under `unsupported`.

Nobody was building it. So I did.

<br>

## 🎙️ Autrans

**Audio for the African voice.** Yorùbá, Pidgin, code-switched English.
Live. Paying users. Built alone to production, then I hired a team around it.

An hour of audio moves like this:

upload → S3 → BullMQ → workers (they die; that's assumed) → diarize →
code-switch pass → Postgres → SSE to the client


Multi-currency billing on Paystack, because Lagos pays in naira and
London pays in pounds and both webhooks arrive twice.

<br>

## What I'm good at

**Systems that expect to fail.** Retries, backoff, idempotency, dead letter.
A worker dying mid-job is a Tuesday, not an incident.

**Money that crosses borders.** Multi-currency, reconciliation, the
duplicate webhook, the failed charge at 2am.

**The AI layer.** Streaming, token economics, eval sets for languages
with no benchmarks. Including knowing when not to use a model at all.

<br>

## Stack

`TypeScript` `Rust` `Python` `Node` `Next.js` `Postgres` `Redis` `BullMQ` `AWS`

Not things I've touched. Things I can tell you the failure modes of.

<br>

---

<p align="center">
Open to remote roles and good teams.<br>
<a href="https://tobilobasulaimon.com">Portfolio</a> ·
<a href="#">CV</a> ·
<a href="#">LinkedIn</a>
</p>
