### Hi there ❤

```bash
function git_corb() {
    if [[ -z "$1" ]]; then
        echo "missing remote branch name for 'git checkout remote branch'"
        return 1
    else
        git checkout -b "$1" origin/"$1"
    fi
}
```
