### dependency-resolver

A very simple demo of dependency resolution using promises. Define "jobs" that have dependencies on each other (see ./example/) and dependency-resolver.jl will run them in the correct order.

#### Quickstart

- `git clone https://github.com/WestleyArgentum/dependency-resolver.git`
- `cd dependency-resolver`
- `julia -e "Pkg.add(\"JSON\")"`
- `julia dependency-resolver.jl ./example/linear.json`
