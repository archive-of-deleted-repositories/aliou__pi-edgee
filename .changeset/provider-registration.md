---
"@aliou/pi-edgee": minor
---

Register the Edgee provider as a complete pi-ai `Provider` via `pi.registerProvider(provider)` instead of the name-plus-config form, with auth resolution that never throws and falls back to an anonymous credential when no key exists, so the model catalog refresh works on vanilla installs.
