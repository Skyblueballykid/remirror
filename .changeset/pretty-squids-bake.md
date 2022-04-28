---
'@remirror/extension-link': minor
---

Add support for `autoLinkAllowedTLDs` which enables the restiction of auto links to a set of Top Level Domains (TLDs). Defaults to a list of all valid TLDs.

Tweak auto link regex to prevent match of single digit domains (i.e. 1.com) and remove support for hostnames ending with "." i.e. "remirror.io."
