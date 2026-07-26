# Standalone Training Software

This folder contains the software used to run controlled technical ear-training exercises.

These tools are part of the project itself—not merely external resources. Each program should make a listening variable repeatable, recordable, and progressively more difficult so that improvement can be demonstrated over time.

## Planned Tools

| Tool | Training purpose | Status |
|---|---|---|
| Frequency Band Trainer | Identify boosted or attenuated frequency regions | Planned |
| Level Difference Trainer | Detect and estimate small level changes | Planned |
| Compression Trainer | Recognize changes in attack, release, and dynamic range | Planned |
| Distortion Trainer | Identify clipping, saturation, and nonlinear artifacts | Planned |
| Imaging Trainer | Evaluate level-, delay-, and frequency-dependent image movement | Planned |
| Automotive Evaluation Tool | Guide and record repeatable in-vehicle listening tests | Planned |

## What Each Tool Should Include

Each software folder should contain:

- The standalone application or source files
- A short explanation of the listening skill
- Setup and operating instructions
- Supported audio formats and system requirements
- Difficulty settings
- Scoring or result output
- Known limitations
- A link to the corresponding exercise and example session log

## Suggested Folder Pattern

```text
training-software/
└── tool-name/
    ├── README.md
    ├── source/
    ├── releases/
    ├── test-audio/
    └── examples/
```

Only include audio that you created, own, or have permission to redistribute. Large compiled applications and audio packages can be linked through GitHub Releases when appropriate.

## Development Principle

The tools should support controlled listening rather than hide the method. A portfolio reviewer should be able to understand what variable changed, how the trial was randomized, how the answer was scored, and how the software connects to the documented training results.
