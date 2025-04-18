# Hinode Module - Template

<!-- Tagline -->
<p align="center">
    <b>A template to define a Hugo module compatible with Hinode</b>
    <br />
</p>

<!-- Badges -->
<p align="center">
    <a href="https://gohugo.io" alt="Hugo website">
        <img src="https://img.shields.io/badge/generator-hugo-brightgreen">
    </a>
    <a href="https://gethinode.com" alt="Hinode theme">
        <img src="https://img.shields.io/badge/theme-hinode-blue">
    </a>
    <a href="https://github.com/anoduck/mod-redirect/commits/main" alt="Last commit">
        <img src="https://img.shields.io/github/last-commit/anoduck/mod-redirect.svg">
    </a>
    <a href="https://github.com/anoduck/mod-redirect/issues" alt="Issues">
        <img src="https://img.shields.io/github/issues/anoduck/mod-redirect.svg">
    </a>
    <a href="https://github.com/anoduck/mod-redirect/pulls" alt="Pulls">
        <img src="https://img.shields.io/github/issues-pr-raw/anoduck/mod-redirect.svg">
    </a>
    <a href="https://github.com/anoduck/mod-redirect/blob/main/LICENSE" alt="License">
        <img src="https://img.shields.io/github/license/anoduck/mod-redirect">
    </a>
</p>

## About

![Logo](https://raw.githubusercontent.com/gethinode/hinode/main/static/img/logo.png)

Hinode is a clean blog theme for [Hugo][hugo], an open-source static site generator. Hinode is available as a
[template][repository_template], and a [main theme][repository]. <!-- This repository maintains a Hugo module to add
[module][module] to a Hinode site. --> Visit the Hinode documentation site for [installation instructions][hinode_docs].

## Contributing

This module uses [semantic-release][semantic-release] to automate the release of new versions. The package uses `husky`
and `commitlint` to ensure commit messages adhere to the [Conventional Commits][conventionalcommits] specification. You
can run `npx git-cz` from the terminal to help prepare the commit message.

## Configuration

This module supports the following parameters (see the section `params.modules` in `config.toml`):

| Setting                   | Default | Description |
|---------------------------|---------|-------------|

## Credits

Pranjal Agrawal - for the Hugo Redirect theme, for which the general idea and parts of code came from.
Mark Dumay - The creator of Hinode.

<!-- MARKDOWN LINKS -->
[hugo]: https://gohugo.io
[hinode_docs]: https://gethinode.com
<!-- [module]: https://example.com -->
[repository]: https://github.com/gethinode/hinode.git
[repository_template]: https://github.com/gethinode/template.git
[conventionalcommits]: https://www.conventionalcommits.org
[husky]: https://typicode.github.io/husky/
[semantic-release]: https://semantic-release.gitbook.io/
