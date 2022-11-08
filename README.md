# Xeros terms


This is Xeros baseball team terms [![textlint](https://github.com/xerosbaseball/terms/actions/workflows/textlint.yml/badge.svg)](https://github.com/xerosbaseball/terms/actions/workflows/textlint.yml)[![Actions Status: deploy](https://github.com/xerosbaseball/terms/actions/workflows/actions.yml/badge.svg)](https://github.com/xerosbaseball/terms/actions/workflows/actions.yml)

## Getting Started

This site use [Hugo](https://gohugo.io/getting-started/quick-start/). To install Hugo you can see [This](https://gohugo.io/getting-started/installing) page

### Install submodules

`
git submodule update -i
`

### Add new content

`
Hugo new <File name>
`

Example

`
hugo new ball_management.ja_jp.md
`

### Start local server

`
hugo server -D
`

or

`
docker-compose up -d
`

### Deploy to GitHub Pages

This process is fully automated by GitHub Actions. Once the update is pushed to the main branch, then automatically updated.
