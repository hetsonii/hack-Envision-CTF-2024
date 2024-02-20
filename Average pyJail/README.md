Average pyJail
=

Just a simple python jail for you guys!!

### Connection: nc misc.avgjail.ctf.teamquark.com 65321

### Author: Gourav Suram


## Solution

Driver Code:
```py
inp = input("Enter payload for eval : ")
signal.alarm(0)
if len(inp) < len('print(secret)') - 1 and 'secret' not in inp:
    print(eval(inp))
else:
    print('Nice try (ig)')
```

From [here](https://stackoverflow.com/questions/633127/viewing-all-defined-variables), I found out about 'globals()' which gave me the flag

![Solution Image](https://github.com/hetsonii/hack-Envision-CTF-2024/assets/75877010/2268c1f0-62d2-4bfc-a536-323a467c524e)


