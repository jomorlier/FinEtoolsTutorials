[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

# FinEtoolsTutorials: Tutorials for FinEtools

## News

- 11/09/2018: Updated for FinEtools v1.0.0.

- 09/19/2018: Separated out all examples from the FinEtools package.


[Past news](oldnews.md)

## How to run

All tutorials work with Julia 1.0, using the [Literate](https://github.com/fredrikekre/Literate.jl) workflow.
This means that in addition to the source files (`.jl`) there are also markdown versions of the tutorials (`.md`).

Get [FinEtools](https://github.com/PetrKryslUCSD/FinEtools.jl).
The FinEtools package is  registered, and hence one can do just
```julia
] add FinEtools
```

Then you should be able to run each tutorial in Julia using `include()`.