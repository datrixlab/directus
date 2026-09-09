---
'@directus/api': patch
---

Fixed the collab permission cache cleaning up metadata for the wrong key on eviction, which leaked tag entries for evicted keys and left surviving entries unable to be invalidated
