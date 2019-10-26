### curdling
--- 
https://github.com/clarete/curdling/

http://clarete.li/curdling/

```py
// curdling/mapping.py
def wheel_version(path):
  return path.split('-')[1]
  
class Mapping(object):
  
  def __init__(self):
    self.requirements = set()
    self.dependencies = defaultdict(list)
    self.stats = defaultdict(int)
    self.errors = defaultdict(dict)
    self.wheels = {}
    self.repeated = []
  
  def count(self, service):
    return self.stats[service]

```

```
```

```
```
