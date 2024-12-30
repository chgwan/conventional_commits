# Conventional_commits

## introduction
A git hook for conventional git commits 

This script follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to conventionalize your git commit. 

## Usage
```
cd <your_project_root_path>
curl https://raw.githubusercontent.com/chgwan/conventional_commits/refs/heads/main/commit-msg -o .git/hooks/commit-msg
chmod u+x .git/hooks/commit-msg
```

## Uninstall
```
cd <your_project_root_path>
rm .git/hooks/commit-msg
```

## Customization
### Add / Remove types
Modify the file .git/hooks/commit-msg line 21
`types=('build' 'docs' 'feat' 'fix' 'perf' 'refactor' 'style' 'test' 'chore' 'ci')`