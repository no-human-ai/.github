<div align="center">

<img src="https://raw.githubusercontent.com/no-human-ai/no_human/main/docs/assets/nh-mark.png" alt="" width="120" height="120">

# no_human

**From ticket to reviewed pull request.**<br>***Free and open-source, on your machine.***

[**The repository →**](https://github.com/no-human-ai/no_human) · [getnohuman.com](https://getnohuman.com) · [Quickstart](https://github.com/no-human-ai/no_human/blob/main/docs/quickstart.md)

</div>

Hand it a ticket — Jira, Linear, monday.com, a GitHub or GitLab issue, or a sentence — and it plans the change, writes it, runs your tests, and hands the work to a second model that never saw it being written, told to refute "done". A tamper guard blocks a net drop in tests before a reviewer token is spent. It opens the pull request and stops: merging stays yours.

Runs on your own machine, on your own Claude subscription or API key (OpenAI Codex is a second backend option). SQLite, your git host, nothing of ours in the middle. MIT.

```bash
uv tool install no-human && nh init && nh doctor
```
