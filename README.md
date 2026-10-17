<div align="center">

<img src="./profile-scan.svg" alt="Profile scan" width="100%"/>

</div>

## Contribution Activity

<div align="center">

<!-- Glowing line graph (like your first screenshot). No workflow needed. -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR-USERNAME&bg_color=0d1117&color=5ff5d0&line=5ff5d0&point=ffffff&area=true&area_color=2fd9b4&hide_border=true" width="100%"/>

</div>

## Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117"/>

</div>

## Snake

<div align="center">

<!-- Needs the GitHub Action in snake.yml (see below). Remove if you skip it. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR-USERNAME/YOUR-USERNAME/output/github-contribution-grid-snake-dark.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/YOUR-USERNAME/YOUR-USERNAME/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

## Featured Projects

| Project | What it does |
|---|---|
| **Brute-force Log Analyzer** | Detects login brute-force attempts from auth logs |
| **Job Application Tracker** | Full-stack app to track applications and statuses |

## Tech

![Python](https://img.shields.io/badge/-Python-0d1117?logo=python&logoColor=5ff5d0)
![JavaScript](https://img.shields.io/badge/-JavaScript-0d1117?logo=javascript&logoColor=5ff5d0)
![TypeScript](https://img.shields.io/badge/-TypeScript-0d1117?logo=typescript&logoColor=5ff5d0)
![React](https://img.shields.io/badge/-React-0d1117?logo=react&logoColor=5ff5d0)
![Linux](https://img.shields.io/badge/-Linux-0d1117?logo=linux&logoColor=5ff5d0)

<!--
SNAKE WORKFLOW: save as .github/workflows/snake.yml in your profile repo

name: Generate Snake
on:
  schedule: [{ cron: "0 */12 * * *" }]
  workflow_dispatch:
  push: { branches: [main] }
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->
