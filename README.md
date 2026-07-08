# HTTP/2 Rapid Reset — CVE-2023-44487

**What it is**
DoS via HTTP/2 stream cancellation flood exhausting server threads. Affects `netty-codec-http2` in `api-gateway`.

**Remediation**
Upgrade to `netty-codec-http2 >= 4.1.100.Final`.
