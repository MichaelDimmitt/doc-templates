# doc-templates

A library of reusable document templates and reference docs for product and software teams.

## Structure

```
doc-templates/
├── Software-Lifecycles-Overview.md   # Reference: how business, product, and SDLC lifecycles nest
└── templates-01/
    └── product/                      # Product management templates
        ├── discovery/                # Before you build
        ├── execution/                # While you build
        ├── launch/                   # When you ship
        └── ongoing/                  # Throughout everything
```

## Reference Docs

| Doc | Description |
|-----|-------------|
| [Software Lifecycles Overview](Software-Lifecycles-Overview.md) | How business, product, SDLC, and other lifecycles relate and nest |

## Templates

See [templates-01/product/README.md](templates-01/product/README.md) for the full template index.

### Quick Reference

| Phase | Templates |
|-------|-----------|
| **Discovery** | Project Brief, PRD, Technical Spec, Persona, Experience Canvas, Product Roadmap |
| **Execution** | Project Plan, Sprint Plan, Status Update, Goals/Signals/Measures, Trade-off Sliders |
| **Launch** | Release Notes, Postmortem, Retrospective |
| **Ongoing** | DACI Decision, Meeting Notes, Team Health Monitor |

## Usage

1. Find the template for your phase in `templates-01/product/<phase>/`
2. Copy it to your project folder
3. Rename it (drop the `-Template` suffix)
4. Fill it in
