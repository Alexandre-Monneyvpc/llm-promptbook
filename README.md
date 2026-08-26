# llm-promptbook

Curated system prompts I actually use day to day

## Installation

```bash
# no dependencies - browse the prompts/ folder
```

## Highlights

- index.json for programmatic access
- Each prompt has usage notes and known failure modes
- Tested against GPT and Claude models
- One prompt per file, easy to diff and review

## Usage

```bash
# copy a prompt into your system message
cat prompts/senior-reviewer.md
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── prompts/
│   ├── eli-junior.md
│   ├── rewrite-pass.md
│   ├── senior-reviewer.md
│   └── sql-helper.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── index.json
```

## Notes

- mostly stable, edge cases remain

## License

MIT. Do whatever you want.
