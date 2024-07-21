```dataview
TABLE WITHOUT ID link(file.name) AS "Session Date", Status, players
from "1-Session Journals"
where (type = "Session Journal")
SORT file.name DESC

# NPCs

```