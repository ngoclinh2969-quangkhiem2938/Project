# Project
- Virtual Memory - Nguyễn Thị Ngọc Linh - 20192969
- File System - Phạm Quang Khiêm - 20192938

## Step modifi

### Step 1:

- Mo file `utils/pintos-gdb`, thay GDBMACROS = _<full duong dan den /src/misc/gdb-macros>_

- Mo `utils/Makfile` sua `LOADLIBES` thanh `LDLIBS`

Mo terminal thu muc `/src/utils`, go `make`

### Step 2:

- Sua trong file `/src/vm/Make.vars`

_Line 7_: sua `bochs` thanh `qemu` 

Mo termianl thu muc `/src/vm`. Go `make`

### Step 3:

Sua file `/utils/pintos`

- Line 103: Sua `bochs` thanh `qemu`
- Line 257: Sua `kernel.bin` thanh full path den kernel.bin (...src/vm/build/kernel.bin)
- Line 621: Sua `qemu-system-i386` thanh `qemu-system-x86_64`

### Step 4:

Sua file `utils/Pintos.pm`

- Line 362: Sua `loader.bin` thanh full path den loader.bin (...src/vm/build/loader.bin)

### Step 5:

- Sua file `.bashrc` tai folder `/home`, them dong sau:

`export PATH=/home/.../pintos/src/utils:$PATH`

### Step 6:

Go `make check` tai `src/vm`

## Lam tuong tu doi voi filesys
