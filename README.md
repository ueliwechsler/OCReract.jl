# OCReract.jl

*A simple Julia wrapper for Tesseract OCR*

[![Build Status](https://travis-ci.org/leferrad/OCReract.jl.svg?branch=master)](https://travis-ci.org/leferrad/OCReract.jl)
[![Coverage Status](https://codecov.io/gh/leferrad/OCReract.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/leferrad/OCReract.jl)
[![Join the chat at https://gitter.im/OCReract.jl](https://badges.gitter.im/OCReract.jl.svg)](https://gitter.im/OCReract-jl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Nowadays, this library only supports Julia v1.0.

## Installation

As with any unregistered package, just use `Pkg.clone()` with the repository url:

```julia
Pkg.clone("https://github.com/leferrad/OCReract.jl.git")
```

## Testing

In a Julia session, run `Pkg.test("OCReract", coverage=true)`, or just run `julia --code-coverage=all --inline=no test/runtests.jl`.

## Next steps
- Make a Dockerfile
- Develop a module for image pre-processing (to improve OCR results)
