- Build
```bash
ghc Minihs.hs Parser.hs -o minihs
```

- Running
if you have rlwrap installed then just invoke:
```bash
./minihs.sh
```
otherwise:
```bash
./minihs
```
however it's recommended to use rlwrap for gud repl experience

- Syntax:
```haskell
3 + 4 * 5
let x 34 in x + 35
let x 34 in x + let y 35 in y
```
