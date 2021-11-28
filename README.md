# autodiff
Naive Haskell Automatic Differentiation

Example use to find the derivative of x^2 at 5
```
ghci
GHCi, version 8.6.5: http://www.haskell.org/ghc/  :? for help
Prelude> :l Dual.hs 
[1 of 1] Compiling Dual             ( Dual.hs, interpreted )
Ok, one module loaded.
*Dual> (derivative (\x -> x * x)) 5
10
```
