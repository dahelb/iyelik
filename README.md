# Türkçe İyelik — Turkish Possessive Forms Trainer

An interactive web app for practicing possessive suffixes (iyelik ekleri) in Turkish.

## About

This app was created entirely through conversational prompting with [Claude](https://claude.ai) by Anthropic. No code was written manually — the HTML, CSS, JavaScript, grammar logic, and word list were all generated and iteratively refined through dialogue with the AI.

## Features

- **Practice mode** — endless drill with random noun + person combinations
- **Quiz mode** — 10-question rounds with scoring
- **Vowel harmony** — suffixes are computed using 4-way Turkish vowel harmony (ı/i/u/ü)
- **Consonant softening** — handles p→b, ç→c, k→ğ, t→d transformations where applicable (e.g. kitap → kitabım, ayak → ayağım)
- **Reference table** — collapsible overview of all possessive endings
- **Streak tracking** — keeps count of correct/incorrect answers and current streak

## How it works

The app presents a Turkish noun with its German translation and a randomly selected person (ben, sen, o, biz, siz, onlar). You type the correct possessive form and get instant feedback.

All exercises use **singular** nouns.

## Tech

Single self-contained HTML file. No frameworks, no build step, no dependencies. Just open it in a browser.

## Live

Hosted via GitHub Pages: https://dahelb.github.io/iyelik/

## License

MIT
