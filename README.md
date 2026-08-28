# breakbench

Open Agent Track 08: harness that breaks a naive in-process agent and reports failures other teams can reuse.

No LLM. No HTTP victim. Stdlib only.

**Live dashboard:** https://cdn.jsdelivr.net/gh/dev-the-dev-while-deving/breakbench@ff6893b/docs/index.html

Run executes the five attacks in-page. Click a fail row for payload, tool_calls, verdict, and `repro`.

```bash
python3 breakbench.py
```
