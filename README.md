# breakbench

Open Agent Track 08: harness that breaks a naive in-process agent and reports failures other teams can reuse.

No LLM. No HTTP victim. Stdlib only.

```bash
python3 breakbench.py
```

Opens http://127.0.0.1:8000. **Run suite** executes five attacks against the toy victim, writes `reports/*.json` and `FAILURES.md`.

```bash
python3 breakbench.py check   # expected: fail, fail, pass, fail, fail
python3 breakbench.py repro prompt_injection
```

Ponytail: `AGENTS.md` and `.cursor/rules/ponytail.mdc`.
