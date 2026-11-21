# Football Draft PWA v4

Setup lets you configure 2-20 draft participants and their names. Cheat sheets can be pasted or uploaded as CSV/JSON. CSV format: Name,Position,Rank,Estimated points. JSON: array of objects with name and position. Host over HTTPS to install as a PWA.

## v5 corrections and resales
- Delete any erroneous purchase after confirmation; linked resale history is also removed.
- Active navigation tab is always recalculated from state, with exactly one highlighted tab.
- Resale action supports windows after rounds 3, 6 and 9. Buyer pays the full winning bid; seller receives the lower of the bid or floor(90% of the original price). Budgets and ownership recalculate automatically.
