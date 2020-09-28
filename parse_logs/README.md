# Parsing logs

## Syzkaller logs
Use dataParser2.py to parse syzkaller logs.

How to use:
```
python3 dataParser2.py <INPUTFILE> <OUTPUTFILE>
```
## Auditd logs

Use auditDataParser2.py to parse auditd logs.

How to use:
```
python3 auditDataParser2.py <INPUTFILE> <OUTPUTFILE>
```

**Note:** Output will include syzkaller made by syz-executor or a.out.