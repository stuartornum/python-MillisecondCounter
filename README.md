# python-MillisecondCounter

A very simple 100% pure python module to get the execution time in millisecond


## Example Usage

```
from MillisecondCounter import ExecutionCounter

ms = ExecutionCounter()

# Do something here
time.sleep(1)

print ms.finish()

# Output
1005
```
