Paths: Added common variants like debug=1 and debug_mode=true.

Matchers:

    Looks for common debug terms in the response body (stack trace, traceback, etc.).

    Includes HTTP 500 status optionally (common in debug error dumps).

Severity: Marked as medium because it could lead to information disclosure but not always direct exploitation.
