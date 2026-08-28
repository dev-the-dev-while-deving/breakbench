# breakbench

Open Agent Track 08: harness that breaks a naive in-process agent and reports failures other teams can reuse.

No LLM. No HTTP victim. Stdlib only.

**Live dashboard:** https://cdn.jsdelivr.net/gh/dev-the-dev-while-deving/breakbench@4e8dcbd/docs/index.html

Click a fail row for payload, tool_calls, verdict, and `repro`.

```bash
python3 breakbench.py
```

Local Run (http://127.0.0.1:8000) re-executes the five attacks. Public page is that same suite, baked.
