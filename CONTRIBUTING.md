If you found a good source of firewall rules info, it'd be awesome if you could contribute a Little Snitch generator for it.

## Adding a new generator

1. Add a gen script that outputs lsrules to STDOUT (make sure it's `chmod +x`)
2. Add necessary steps to .github/workflows/deploy.yml: a step for running your script and dumping the output into a file: `./build/[app-name].lsrules`, and a step that deploys the gist. Use existing steps for reference. Since you can't create a gist as me, please **leave gist_url blank**, and I will take care of creating the gist.
3. Add a readme list entry (make sure it's alphabetized). In the entry's description provide the URL where your generator gets its info. I will add the gist link myself once I create it.

## Programming language for gen-* files

I prefer these to be written in ruby or shell (i.e. sh, bash). That said, I'll accept other languages if the script is not too complex, consists of a single file, runs on `ubuntu-latest` in Github Actions without additional dependencies, and isn't a compiled binary.
