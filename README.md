# doc-templates

A library of reusable document templates and reference docs for product and software teams.

## Structure

```
doc-templates/
├── Software-Lifecycles-Overview.md   # Reference: how business, product, and SDLC lifecycles nest
└── Templates-01/
    └── Product/                      # Product management templates
        ├── Discovery/                # Before you build
        ├── Execution/                # While you build
        ├── Launch/                   # When you ship
        └── Ongoing/                  # Throughout everything
```

## Reference Docs

| Doc | Description |
|-----|-------------|
| [Software Lifecycles Overview](Software-Lifecycles-Overview.md) | How business, product, SDLC, and other lifecycles relate and nest |

## Templates

See [Templates-01/Product/README.md](Templates-01/Product/README.md) for the full template index.

### Quick Reference

| Phase | Templates |
|-------|-----------|
| **Discovery** | Project Brief, PRD, Technical Spec, Persona, Experience Canvas, Product Roadmap |
| **Execution** | Project Plan, Sprint Plan, Status Update, Goals/Signals/Measures, Trade-off Sliders |
| **Launch** | Release Notes, Postmortem, Retrospective |
| **Ongoing** | DACI Decision, Meeting Notes, Team Health Monitor |

## Usage

1. Find the template for your phase in `Templates-01/Product/<Phase>/`
2. Copy it to your project folder
3. Rename it (drop the `-Template` suffix)
4. Fill it in

## File Naming Convention

Business documents in this repo use **Train-Case**: each word capitalized, separated by hyphens (e.g. `Project-Brief-Template.md`, `PRD-Template.md`). Acronyms stay fully uppercase.

Development files (scripts, config, tooling) may follow a different convention such as kebab-case (`my-script.sh`) per the norms of the language or toolchain involved.
