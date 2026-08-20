<div align="center">

<img src="https://raw.githubusercontent.com/no-human-ai/no_human/main/docs/assets/nh-mark.png" alt="" width="140" height="140">

# no_human

**From ticket to reviewed pull request.**<br>***Free and open-source, on your machine.***

[![latest release](https://img.shields.io/github/v/release/no-human-ai/no_human?label=release&color=4C9AFF)](https://github.com/no-human-ai/no_human/releases/latest) [![CI](https://img.shields.io/github/actions/workflow/status/no-human-ai/no_human/ci.yml?branch=main&label=CI)](https://github.com/no-human-ai/no_human/actions/workflows/ci.yml) [![python 3.12+](https://img.shields.io/badge/python-3.12%2B-blue)](https://www.python.org/) [![license MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/no-human-ai/no_human/blob/main/LICENSE)

[getnohuman.com](https://getnohuman.com) · [Quickstart](https://github.com/no-human-ai/no_human/blob/main/docs/quickstart.md) · [Docs](https://github.com/no-human-ai/no_human/blob/main/docs/README.md) · [Watch it work a sprint](https://getnohuman.com/demo)

[![Download for macOS](https://img.shields.io/badge/Download%20for-macOS-4C9AFF?style=for-the-badge)](https://github.com/no-human-ai/no_human/releases/latest) [![Download for Windows](https://img.shields.io/badge/Download%20for-Windows-4C9AFF?style=for-the-badge)](https://getnohuman.com/) [![Download for Linux](https://img.shields.io/badge/Download%20for-Linux-4C9AFF?style=for-the-badge)](https://getnohuman.com/)

<a href="https://getnohuman.com/"><img src="https://raw.githubusercontent.com/no-human-ai/no_human/main/docs/assets/hero-loop-poster.jpg" alt="The no_human board: one task waiting on a question in Needs answer, four tasks working in parallel, one pull request ready for review." width="880"></a>

<sub>▶ <a href="https://getnohuman.com/">Watch the loop</a> — a ticket in, a reviewed pull request out; the whole loop in 57 seconds.</sub>

</div>

The AI coding factory you <ins>**can trust**</ins>:

- **A plan before any code**, from the ticket plus what it finds in your repo.
- **An adversarial review.** A different model, fresh context, read-only tools,
  told to refute "done". You get a pass/fail checklist citing file and line —
  never a numeric self-score.
- **A tamper guard.** Deleted tests, new skips, an assertion turned into a
  tautology — blocked before a reviewer token is spent.
- **Proof the fix fixed the bug.** For a bug fix, the tests offered as evidence
  must fail at the merge base and pass on the new tree — the reproduction gate
  enforces that, and you can require it for every change.
- **Your tests run**, locally and optionally through your CI.
- **An honest stop.** When it cannot finish, it parks with one specific question
  instead of inventing a plausible diff.

```bash
uv tool install no-human   # or: pipx install no-human — the wheel ships the board
nh init && nh doctor       # token, config, first repo; then prove the install is real
```

<div align="center">

[**Repository →**](https://github.com/no-human-ai/no_human)

</div>
