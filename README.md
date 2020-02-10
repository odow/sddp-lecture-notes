## SDDP.jl notebook install instructions

1. Download and install Julia from https://julialang.org/downloads/
2. Move the contents of this folder somewhere memorable, e.g., `~/Documents/large-scale`
3. Open Julia. You have two options.
    - Via the command line (`terminal`, `cmd.exe`, etc.)
    ```
    cd ~/Documents/large-scale
    julia --project=.
    ```
    - By opening the Julia REPL (e.g., from application folder, program menu etc.)
    ```
    cd("~/Documents/large-scale")
    import Pkg
    Pkg.activate(".")
    ```
4. Open IJulia:
    ```
    julia> using IJulia
    julia> IJulia.notebook(dir=".")
    ```
5. A browser window will open, and away you go.

Note: the first time you use Julia, it can take a long time to load because it has to
download and install a lot of packages. Same goes for when you use a new package for the
first time.
