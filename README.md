# resume

latex resume template, organized by section.

## structure

```
resume/
├── main.tex          # entry point, just pulls everything together
├── config.tex        # packages, custom commands, page layout
└── sections/
    ├── heading.tex   # name, contact info
    ├── education.tex
    ├── experience.tex
    ├── projects.tex
    └── skills.tex
```

## usage

clone it, edit whatever section you need, compile with:

```bash
pdflatex main.tex
```

or use [overleaf](https://overleaf.com) if you'd rather not deal with a local latex install.

## notes

- based on the classic [Jake's Resume](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs) template
- each section is its own file so you're not scrolling through 300 lines to fix a typo in your job title
