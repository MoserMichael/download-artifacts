
### Script for downloading artifacts


The bash script ```download-github-artifacts.sh``` for downloading the artifacts of the latest release for a given github repo of a given user.

How to use:

```
./download-github-artifacts.sh -u <github user> -r <github reporsitory> [-v -h]

for a given github user and repository: downloads all artifacts for the latest release .

    -u <github user>        - github user
    -r <github repository>  - repository of the given user
    -o <outputdir>          - optional (default: download to current dir

    -v                      - verbose output
    -h                      - show this help text
```

### Example usage:

```
./download-github-artifacts.sh -u robxu9 -r bash-static
```

Downloads artifacts of this wonderful repository: https://github.com/robxu9/bash-static


### Requirements

The script requires ```curl``` and ```jq```
