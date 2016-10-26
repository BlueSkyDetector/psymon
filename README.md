# Python System Monitor (Psymon)
A cross-platform, task and performance monitor.

----
In this repository, I fixed some code for working with recent libraries.

Original code was crashed with recent libraries like following.

```
$ psymon
Traceback (most recent call last):
  File "./psymon", line 33, in <module>
    from psutil.error import NoSuchProcess, AccessDenied
ImportError: No module named error
```
