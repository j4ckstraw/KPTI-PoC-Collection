## compile

open C:\Program Files (x86)\Microsoft Visual Studio 12.0\Common7\Tools\Shortcuts
click VS2013 x64 本机工具命令提示

>
>D:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\bin\amd64>cd /d F:\SystemFolders\Desktop\KPTI-PoC-Collection
>F:\SystemFolders\Desktop\KPTI-PoC-Collection>ml64 /c /Fo wina.obj win.asm
>Microsoft (R) Macro Assembler (x64) Version 12.00.31101.0
>Copyright (C) Microsoft Corporation.  All rights reserved.
>
>Assembling: win.asm
>
>F:\SystemFolders\Desktop\KPTI-PoC-Collection>cl /c win.cpp  /Fo:winb.obj
>用于 x64 的 Microsoft (R) C/C++ 优化编译器 18.00.31101 版
>版权所有(C) Microsoft Corporation。  保留所有权利。
>
>win.cpp
>
>F:\SystemFolders\Desktop\KPTI-PoC-Collection>link /out:win.exe wina.obj winb.obj
>Microsoft (R) Incremental Linker Version 12.00.31101.0
>Copyright (C) Microsoft Corporation.  All rights reserved

## run

>F:\SystemFolders\Desktop\KPTI-PoC-Collection>win.exe
>0x1000: guess: 0x40, real:0x00
>0x1001: guess: 0x40, real:0x00
>0x1002: guess: 0x40, real:0x00
>0x1003: guess: 0x40, real:0x00
>0x1004: guess: 0x00, real:0x00
>...

Am I wrong :(
