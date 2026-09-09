---
'posthog-node': patch
---

Honor `evaluation_runtime` during local evaluation — flags marked client-side only are no longer evaluated locally and resolve to `undefined`, matching what `/flags` returns for a server SDK.
