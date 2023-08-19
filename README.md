# bootstrap-seen-compiler

porting the compiler from rust to seen.

## Status
The current compiler is written in rust, `seen` is capable of importing rust modules, <br>
if a rust language feature used in the compiler code has a `seen` equivalent, <br>
the code will be rewritten with its `seen` equivalent and the rest of the rust code will be imported as it is.<br><br>
New compiler features that are required to finish the bootsrapping process will be added to the [Seen Compiler](https://github.com/abukhadra/seen-compiler) repository as needed until a self-hosting `seen` compiler is obtained.


## Building from source
- obtain a copy of the `seen` compiler / editor, follow instructions in the `seen` repository readme file : [Building from source](https://github.com/abukhadra/seen#building-from-source)
- get a copy of the bootsrap-seen-compiler  
```
    git clone https://github.com/abukhadra/bootstrap-seen-compiler.git
```
- open the `bootsrap-seen-compiler` project using the `seen` editor , then click on build