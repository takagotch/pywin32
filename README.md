### pywin32
---
https://sourceforge.net/projects/pywin32/

https://github.com/mhammond/pywin32

```py
# win32/lib/dbi.py
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

# win32/lib/winnt.py
TransactionOutcomeUndetermined = 1
TransactionOutcomeCommitted = 2
TransactionOutcomeAborted = 3

TransactionStateNormal = 1
TransactionStateIndoubt = 2
TransactionStateCommittedNotify = 3
```

```
```

```
```


