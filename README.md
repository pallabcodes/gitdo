# GitDo - Git Practices Repository

This repo is all about git practices for day to day plus advanced commands.

The commands for day to day work mostly: add, commit, push, and ammendaa

Test Changed

Added themes with transparency for iterm (mac) and kitty (linux)

## Testing Easigit

This repository is used to test the [easigit](https://github.com/picon/easigit) TUI application.

### Quick Start
A local copy of easigit is available for immediate testing:
```bash
./easigit-local
```

### Building from Source
To test the latest changes:
1. Build easigit: `cd ../easigit && cargo build`
2. Run the test script: `bash test-easigit.sh`

The test script will:
- Check that the easigit binary exists
- Show current git status
- Launch easigit in the current directory

### Alternative Methods
- Direct path: `/Users/picon/Learning/c-or-c-plus-plus/easigit/target/debug/easigit`
- Update local copy: `cp ../easigit/target/debug/easigit ./easigit-local`
