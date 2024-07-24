
# HawkLoader

An Indirect System Call Based Shellcode Loader Written Fully In D.

## How Does It Work?

HawkLoader utilizes indirect D's inline assembler to execute indirect system call stubs based on my project [DSysWhispers](https://github.com/dk0m/DSysWhispers), Check it out to learn how it works.


## Compilation

```
$ dmd loader.d -i syscalls.d
```

To execute it directly, Run this:

```
$ rdmd loader.d
```
