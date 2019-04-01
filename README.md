### pywin32
---
https://sourceforge.net/projects/pywin32/

https://github.com/mhammond/pywin32

```py
import warnings
warning.warn(
  "dbi module is obsolete, code should now use native python datetime and buffer/memoryview objects",
  DeprecationWarning)
  
import datetime
dbDate = dbiDate = datetime.datetime

try:
  dbRaw = dbRaw = buffer
except NameError:
  dbRaw = dbiRaw = memoryview
  
from odbc import *
```

```
```

```
```


