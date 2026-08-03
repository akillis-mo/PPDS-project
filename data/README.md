# Data directory

Use the following organization:

```text
data/
├── raw/
│   ├── arm/       # Original ARM data
│   └── x86/       # Original x86 data
└── processed/     # Validated and model-ready data
```

Do not modify files in `raw/`. Any cleaning, correction, exclusion, or transformation should produce a new file in `processed/` and be reproducible from the notebooks.

The dataset files themselves are ignored by Git.

