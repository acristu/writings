# PROs


# CONs

## git lets you commit in detached head

Some people committed by mistaked in detached head submodules, did not notice push did not happen and commited the sha in the parent.

Obviously this would cause an error like this:

```
Fetched in submodule path 'path/to/submodule', but it did not contain 673e92aad79fc3d9519ff2ceea7f01a8ea3ecaf3. Direct fetching of that commit failed.
```

Solution, for dev envs always checkout the branched for all submodules:

```
TBD one-liner to checkou branches
```
