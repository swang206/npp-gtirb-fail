This is a repo to report a specific issue for gtirb.

notepad++.exe cannot reassemble

D:\hg\notepad-plus-plus\PowerEditor\bin>ml64 npp.asm /link /subsystem:windows /entry:__EntryPoint /machine:x64
Microsoft (R) Macro Assembler (x64) Version 14.30.30423.0
Copyright (C) Microsoft Corporation.  All rights reserved.

 Assembling: npp.asm
Microsoft (R) Incremental Linker Version 14.30.30423.0
Copyright (C) Microsoft Corporation.  All rights reserved.

/OUT:npp.exe
npp.obj
/subsystem:windows
/entry:__EntryPoint
/machine:x64
npp.obj : error LNK2001: unresolved external symbol __imp_COMCTL32@17
npp.obj : error LNK2001: unresolved external symbol COMCTL32@17
npp.obj : error LNK2001: unresolved external symbol __imp_COMCTL32@410
npp.obj : error LNK2001: unresolved external symbol COMCTL32@410
npp.obj : error LNK2001: unresolved external symbol __imp_COMCTL32@412
npp.obj : error LNK2001: unresolved external symbol COMCTL32@412
npp.obj : error LNK2001: unresolved external symbol __imp_COMCTL32@413
npp.obj : error LNK2001: unresolved external symbol COMCTL32@413
npp.obj : error LNK2001: unresolved external symbol __imp_OLEAUT32@2
npp.obj : error LNK2001: unresolved external symbol OLEAUT32@2
npp.obj : error LNK2001: unresolved external symbol __imp_OLEAUT32@6
npp.obj : error LNK2001: unresolved external symbol OLEAUT32@6
npp.obj : error LNK2001: unresolved external symbol __imp_SHELL32@165
npp.obj : error LNK2001: unresolved external symbol SHELL32@165
npp.exe : fatal error LNK1120: 14 unresolved externals