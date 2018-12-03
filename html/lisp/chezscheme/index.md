# ChezScheme

## ChezScheme源码分析

### nanopass框架
[Andy Keep's scheme-to-c demo](scheme-to-c.html)

### Hygienic Macro Expander

### 栈/continuation/GC

### bootstrap

### s目录

nanopass定义的language:

base-lang.ss
expand-lang.ss
np-languages.ss

nanopass定义的pass:

cpnanopass.ss
cp0.ss
cprep.ss
cpvalid.ss
cpletrec.ss
cpcommonize.ss
cpcheck.ss

interpret.ss
compile.ss

ppc32.ss
arm32.ss

其他与机器相关的文件:

x86.ss
x86_64.ss

与prim相关:

mathprims.ss
primdata.ss
priminfo.ss
primref.ss
prims.ss
primvars.ss

macro expander:

syntax.ss

### c目录

### configure/makefiles
