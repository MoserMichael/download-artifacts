
### Script for downloading artifacts

The script ```download-github-artifacts.sh``` downloads the artifacts of the latest release for a github repository on a given github user.

How to use:

```
./download-github-artifacts.sh -h
./download-github-artifacts.sh -u <github user> -r <github reporsitory> [-v -h]

for a given github user and repository: downloads all artifacts for the latest release .

    -u <github user>        - github user
    -r <github repository>  - repository of the given user
    -o <outputdir>          - optional (default: download to current dir
```

### Example usage:

```
./download-github-artifacts.sh -u robxu9 -r bash-static
```

Downloads artifacts of this wonderful repository: https://github.com/robxu9/bash-static


### requirements

The script requires ```curl``` and ```jq```
