---
'@modelcontextprotocol/client': patch
'@modelcontextprotocol/core-internal': patch
---

Follow permitted redirects without waiting for their response bodies. Start canceling the discarded body instead of reading it to completion, and do not wait for cancellation of a cloned response. Responses that are returned to the caller keep their bodies readable; the redirect policy and hop limit are unchanged.
