# deadlock-app

Demonstrates the occurence of a deadlock ('ill give you mine if you give me yours ...).

See the dump folder for a capture of the thread dump.

## Taking Dump

```
jps -lV

jstack <PID> > threaddump.txt
```