NFA
---
The following diagrams illustrate a `State` structure for 'foo'

```
0x0000000100500020
+---------------------------+
| State:                    |
| c: 'f'                    |
| out: 0x0000000100500040   |
| out1: NULL                |
| lastlist = 0              |
+-------------+-------------+
              |
              |
              +-----+
                    |
0x0000000100500040  |
+-------------------+-------+
| State:                    |
| c: 'o'                    |
| out: 0x0000000100003038   |
| out1: NULL                |
| lastlist = 0              |
+-------------+-------------+
              |
              |
              +-----+
                    |
0x0000000100003038  |
+-------------------+-----------+
| +---------------------------+ |
| | State:                    | |
| | c: 256                    | |
| | out: NULL                 | |
| | out1: NULL                | |
| | lastlist = 0              | |
| +---------------------------+ |
+-------------------------------+
```
