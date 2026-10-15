---
"@shadcn/react": patch
---

Set `data-pending-scroll` on the MessageScroller root and viewport to the pending `defaultScrollPosition` (`"end"` or `"last-anchor"`), and remove it before the opening position is measured, so styles can pin a server-rendered `"end"` transcript to the bottom before hydration.
