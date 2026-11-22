# Mathieu De Gracia

Backend lead and software architect, with nearly fifteen years of professional PHP behind me, and Laravel since version 4. Lead Chapter Backend at GlobalExam, co-founder of Laravel France, author of PHP The Readability Way.

I build with AI agents, and I build the tools that keep their code understandable.

## 🤖 Building with agents

- **[Établi](https://github.com/DeGraciaMathieu/etabli)** 🔥: a self-hosted forge where an agent writes the code and the decisions stay with you. Today, Claude Code runs headless on an EC2 instance, driven from Telegram, and only comes back to you for what is yours to decide. No inbound port: long polling and SSH over SSM.
- **[What moved](https://github.com/DeGraciaMathieu/what-moved)** 🔥: a GitHub Action that maps what a pull request moved among your PHP contexts and their dependencies. Reviewing a pull request written by an AI starts with a map, not a diff. The analysis lives in [what-moved-core](https://github.com/DeGraciaMathieu/what-moved-core).
- **[quotabar](https://github.com/DeGraciaMathieu/quotabar)**: a macOS menu bar app showing where you stand on your Claude Code plan limits.
- **[claude-game-refactor-plugin](https://github.com/DeGraciaMathieu/claude-game-refactor-plugin)**: a Claude Code plugin that turns a single-file HTML game prototype into a split, tested and documented codebase.
- **[tiny-shakespeare-gpt](https://github.com/DeGraciaMathieu/tiny-shakespeare-gpt)**: a minimal character-level GPT, about a million parameters in a single file, built from scratch to understand how a GPT works.

## 🏛️ Keeping architecture readable

Tools to measure and explain the structure of a PHP codebase.

- **[php-dep](https://github.com/DeGraciaMathieu/php-dep)**: extracts the class dependency graph of a project as JSON, covering inheritance, interfaces, traits, injections, instantiations, static calls, attributes. Files are parsed in parallel. Two tools build on it: [php-dep-dashboard](https://github.com/DeGraciaMathieu/php-dep-dashboard), an interactive graph explorer in the browser, and [php-dep-louvain](https://github.com/DeGraciaMathieu/php-dep-louvain), which detects communities of tightly coupled classes.
- **[php-class-dependencies-analyzer](https://github.com/DeGraciaMathieu/php-class-dependencies-analyzer)**: measures how classes and components depend on each other, finds dependency cycles and breaks of the Stable Dependencies Principle, then fails your CI when the architecture drifts.
- **Smaller detectors, one signal each:** [code smells](https://github.com/DeGraciaMathieu/php-smelly-code-detector) · [vocabulary](https://github.com/DeGraciaMathieu/php-wording-detector) · [arguments](https://github.com/DeGraciaMathieu/php-arguments-detector) · [line length](https://github.com/DeGraciaMathieu/php-line-length-detector) · [variable lifetime](https://github.com/DeGraciaMathieu/php-variable-lifetime-analyzer) · [Git history](https://github.com/DeGraciaMathieu/php-git-insights-analyzer)
## 🔭 Explorations

Going back to where ideas come from: an old architecture and academic algorithms, rebuilt in PHP to understand them.

- **[ericsson-1967](https://github.com/DeGraciaMathieu/ericsson-1967)**: a proof of concept of a blocks-and-signals architecture, inspired by the Ericsson telephone exchanges of the late 1960s. No code describes the business scenario: the behaviour emerges from named signals travelling between fixed blocks.
- **[algo-louvain-php](https://github.com/DeGraciaMathieu/algo-louvain-php)** and **[GirvanNewman](https://github.com/DeGraciaMathieu/GirvanNewman)**: two community detection algorithms from graph theory, implemented in PHP.
- **[php-rasch](https://github.com/DeGraciaMathieu/php-rasch)**: the Rasch model from item response theory, implemented in PHP.

## 🛠️ Applications

- **[Trivia](https://github.com/DeGraciaMathieu/trivia)**: the stories behind the conventions of our trade, like the `X-` prefix, `chmod 777`, Ariane 501 or the core dump. A Laravel site with about seventy stories, and an MCP server secured with OAuth 2.1 so agents can read and write them.
- **[devdock](https://github.com/DeGraciaMathieu/devdock)**: a macOS menu bar app for the developer's daily routine: open a project, see what is uncommitted or unpushed, find which process listens on which port.
- **[coreload](https://github.com/DeGraciaMathieu/coreload)**: a macOS menu bar app showing which processes load your CPU, counted in cores.
- **[pdf-translate-inplace](https://github.com/DeGraciaMathieu/pdf-translate-inplace)**: translates English PDFs to French in place, keeping the original layout, images and fonts.

## 🎮 Game lab

Games are where I push AI-assisted development furthest. Since summer 2026 I have built around thirty prototypes. Each one starts as a single HTML file, then my Claude Code plugin, [claude-game-refactor-plugin](https://github.com/DeGraciaMathieu/claude-game-refactor-plugin), turns it into native ES modules with tests and documentation. All the games below went through it (most are in French):

| Game | What it is |
| --- | --- |
| [Tenir la charge](https://github.com/DeGraciaMathieu/hold-the-load) | Place servers, caches, queues and databases, then watch your infrastructure take the traffic, the outages and the attacks. 19 missions, a growth mode and a daily challenge. |
| [Tête Carrée](https://github.com/DeGraciaMathieu/tete-carree) | Arena survival against waves of zombies, with keyboard, touch or gamepad. Test and performance CI, [published on itch.io](https://857wpwth.itch.io/tete-carree). |
| [Livre-jeu](https://github.com/DeGraciaMathieu/gamebook-engine) | A choose-your-own-adventure gamebook for phones, with dice rolls and combat. |
| [old-school-wargame](https://github.com/DeGraciaMathieu/old-school-wargame) | A turn-based hex wargame: two armies of equal strength on a map drawn at random each game. Eight turns, against an AI or two players on one screen. |
| [Dwarf](https://github.com/DeGraciaMathieu/dwarf) | A colony simulation inspired by Dwarf Fortress, rendered in ASCII. You give orders, the dwarves decide. |
| [Contrée](https://github.com/DeGraciaMathieu/contree) | A solitaire hex-tile game: build a country by closing mountains, drawing rivers and surrounding villages. |

## ✍️ Writing and community

- Co-founder of **[Laravel France](https://laravel-france.com)**, where I write about Laravel, architecture and now AI.
- **[PHP The Readability Way](https://php-the-readability-way.fr)**: articles on making PHP code easier to read.
