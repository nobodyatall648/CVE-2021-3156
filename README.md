# CVE-2021-3156
## checking CVE-2021-3156 vulnerability & patching script

CVE-2021-3156 description:

Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via "sudoedit -s" and a command-line argument that ends with a single backslash character.


### To check for CVE-2021-3156 vulnerability:
```
python3 CVE-2021-3156_checker.py
```

### To patch CVE-2021-3156 vulnerability:
```
chmod +x ./CVE-2021-3156_patcher.sh && ./CVE-2021-3156_patcher.sh
```

### PoC image can be found in /PoC_Images directory.