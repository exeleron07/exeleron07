<p align="center">
  <img src="https://github.com/exeleron07/exeleron07/blob/main/assets/1.png" alt="Header" width="500">
</p>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=Junior+Devops+Engineer;Always+Learning+Always+Curios;)](https://git.io/typing-svg)

<img boder="2px" src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" min-width="400px" max-width="400px" width="400px" height="300px" align="right" alt="Error to load the image">

<div align="left">
  <h3> 👋 Hi there, I'm Vladislav </h3>
  <p>&nbsp;Всем привет! Меня зовут Владислав, мне 21 год и я начинающий DevOps-инженер. Я учусь всему понемногу и имею желание развиваться</p>
</div>

### Languages and Tools
![Linux](https://img.shields.io/badge/-Linux-010409?style=for-the-badge&logo=linux)
![Docker](https://img.shields.io/badge/-Docker-010409?style=for-the-badge&logo=docker)
![Ansible](https://img.shields.io/badge/-Ansible-010409?style=for-the-badge&logo=ansible)
![GIT](https://img.shields.io/badge/-GIT-010409?style=for-the-badge&logo=git)
![Jenkins](https://img.shields.io/badge/-Jenkins-010409?style=for-the-badge&logo=jenkins)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-010409?style=for-the-badge&logo=kubernetes)
![Python](https://img.shields.io/badge/-Python-010409?style=for-the-badge&logo=Python)

### Follow Me
[![Vkontakte](https://img.shields.io/badge/-VKONTAKTE-010409?style=for-the-badge&logo=VK)](https://vk.com/vlad_versh)
[![Telegram](https://img.shields.io/badge/-Telegram-010409?style=for-the-badge&logo=Telegram)](https://t.me/exeleron01)

![Profile banner](https://i.imgur.com/VNP2tTx.gif)

## 🐍 Contribution Snake
# snk

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

**github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```
