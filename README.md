<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>
    
```python
​from __future__ import annotations
import json
from dataclasses import asdict, dataclass


@dataclass
class grtvishnu:
    languages: tuple[str, ...] = ("Dart","R","Python", "JS", "Go")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "DynamoDB")
    ongoing:   tuple[str, ...] = ("Flutter", "Flask", "Django")

    def jsonify(self):
        return json.dumps(asdict(self), indent=4)


grtvishnu = grtvishnu()
print(grtvishnu.jsonify())
​
```
</h3>
