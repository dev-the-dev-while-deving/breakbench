# breakbench

Open Agent Track 08: harness that breaks a naive in-process agent and reports failures other teams can reuse.

No LLM. No HTTP victim. Stdlib only.

**Live dashboard (text/html, Run executes in-page):** https://cdn.githubraw.com/dev-the-dev-while-deving/breakbench/13ddb5eba86a72e6f19067a434f3768ae11456f7/docs/index.html

Run executes the five attacks in-page. Click a fail row for payload, tool_calls, verdict, and `repro`.

```bash
python3 breakbench.py
```
