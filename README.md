# Hi, I'm Cheerstopriya

I build open-source Python tooling for safer, more testable AI-agent systems. I'm interested in software engineering roles involving Python, developer tools, testing, security, and agent infrastructure.

![AuthDrift authority-revocation workflow](https://raw.githubusercontent.com/cheerstopriya/authdrift/main/docs/assets/authdrift-social-preview.jpg)

## Featured project

### [AuthDrift](https://github.com/cheerstopriya/authdrift)

**Can an AI agent still commit a tool effect after its authority is revoked?**

AuthDrift is an MIT-licensed Python test harness that injects a confirmed authority change into a running workflow, resumes the same trajectory, and verifies the authoritative sink state.

[![PyPI](https://img.shields.io/pypi/v/authdrift-harness)](https://pypi.org/project/authdrift-harness/)
[![Tests](https://github.com/cheerstopriya/authdrift/actions/workflows/tests.yml/badge.svg)](https://github.com/cheerstopriya/authdrift/actions/workflows/tests.yml)
[![Python](https://img.shields.io/pypi/pyversions/authdrift-harness)](https://pypi.org/project/authdrift-harness/)

```text
authority valid -> agent observes -> confirmed revocation
                                      -> same run resumes -> did the sink change?
```

- Deterministic mid-flight authority-change injection
- Independent revocation confirmation
- Authoritative sink-state verification
- Vulnerable and corrected refund, delegation, and session fixtures
- No model credential required for the controlled examples

**Try it:** [installation and runnable demo](https://github.com/cheerstopriya/authdrift#installation-and-runnable-demo)  
**Test your agent:** [integration guide](https://github.com/cheerstopriya/authdrift/blob/main/docs/integrating-your-agent.md)

## Current focus

- AI-agent authorization and tool boundaries
- Security regression testing
- Python developer tooling
- Reproducible experiments and release engineering

I'm open to software engineering opportunities and useful open-source collaborations.
