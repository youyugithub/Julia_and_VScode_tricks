# Julia and VScode tricks

## VScode tricks
```
Comment lines: Command + /
Reindent lines: Shift + option(alt) +F
```

## Julia tricks

Include:
```
include("xxxx.jl")
```

Time a code section:
```
start = time()
f(x)
elapsed = time() - start
Random.sum(nobs, dims=1)
```

Column sums:
```
Random.sum(AA, dims=1)
```
