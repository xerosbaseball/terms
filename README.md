## How to build

## Getting Started
This site use [Hugo](https://gohugo.io/getting-started/quick-start/). To install Hugo you can see [This](https://gohugo.io/getting-started/installing) page

### Install submodules
```
git submodule update -i
```

### Add new content
```
Hugo new <File name>
```

Example
```
hugo new ball_management.ja_jp.md
```

### Start local server
```
hugo server -D
```

### Deploy to GitHub Pages
This process is fully automated by GitHub Actions. Once the update is pushed to the main branch, then automatically updated.

### Contribution
You need follow 2 steps below.
- Create Issue
- Create Pull request
Once both steps are completed the repository owner will merge to main branch
