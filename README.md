# breakbench

Open Agent Track 08: harness that breaks a naive in-process agent and reports failures other teams can reuse.

No LLM. No HTTP victim. Stdlib only.

**Live dashboard (Run executes in-page):** https://cdn.jsdelivr.net/gh/dev-the-dev-while-deving/breakbench@37e90f8/docs/index.html

Click a fail row for payload, tool_calls, verdict, and `repro`.

```bash
python3 breakbench.py
```
