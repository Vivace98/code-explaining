# code-explaining

AI-assisted research code explanation skills for statistics, demography, social science research, and machine learning workflows.

Designed for Codex / Claude-style skill workflows.

---

# Skills

## `python-code-explain`

Explains Python research code in a structured, beginner-friendly, and workflow-oriented way.

Focus areas:

- statistics workflows
- demographic research code
- survey data analysis
- machine learning pipelines
- research-oriented Python programming
- package and model explanation

The skill emphasizes:

- overall workflow understanding
- package and tool interpretation
- line-by-line reasoning
- statistical intuition behind the code
- beginner-friendly explanation structure

---

## `r-code-explain`

Explains R research code used in statistics, demography, survey analysis, and quantitative social science workflows.

Focus areas:

- survey-weighted analysis
- regression modeling
- demographic workflows
- data preprocessing
- visualization
- statistical package explanation
- modeling logic reconstruction

The skill emphasizes:

- workflow-level understanding
- statistical reasoning
- package interpretation
- line-by-line explanation
- beginner-friendly research learning

---

# Templates

## `python_explain_note.md`

Reusable explanation template for organizing Python code interpretation notes.

The template structures explanations into:

- overall purpose
- packages and tools
- workflow logic
- line-by-line explanation
- statistical interpretation
- modeling intuition

---

## `r_explain_note.md`

Reusable explanation template for organizing R code interpretation notes.

The template structures explanations into:

- workflow purpose
- package explanation
- modeling logic
- statistical interpretation
- step-by-step code explanation
- research workflow context

Designed for research note-taking and learning workflows.

---

# Repository Structure

```text
code-explaining/
│
├── README.md
│
├── python-code-explain/
│   ├── SKILL.md
│   │
│   └── templates/
│       └── python_explain_note.md
│
└── r-code-explain/
    ├── SKILL.md
    │
    └── templates/
        └── r_explain_note.md
```

---

# Installation / Usage

Place the repository folders inside the `skills/` directory of your Codex or Claude workflow environment.

Example:

```text
codex-project/
│
├── skills/
│   └── code-explaining/
│       ├── python-code-explain/
│       └── r-code-explain/
│
└── ...
```

The skills can then be invoked directly by the agent.
