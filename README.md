# merge-to-pdf

Merge all files in `./input` to `./output/output.pdf`.
This uses the Docker image `debian:testing-slim`, and installs some tools to do the actual merging.


# How to use

1. Put your input files into `./input`
1. Make sure they are named correctly (i.e., their order according to `ls -v` is what you want them to be in the output)
1. Run any of the available variants
1. Use the result in `./output/output.pdf`


# Available variants

Check the directory `./variants` for all available variants.

## Ghostscript

```sh
> docker-compose -f ghostscript.yml up
```
