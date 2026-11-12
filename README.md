# Video Editing Skills

Three reusable workflow guides for editing short-form videos. Each skill describes its required inputs, editing steps, and quality checks.

## Included skills

| Skill | What it does |
| --- | --- |
| `spoken-kinetic-captions` | Reveals emphasis text in sync with speech, one word or short group at a time. |
| `follow-button-cta` | Creates an end-of-video profile card and animated follow-button prompt with synchronized click audio. |
| `past-video-gallery` | Moves earlier video covers behind the speaker in a gallery-style carousel. |

## Repository layout

```text
skills/
├── spoken-kinetic-captions/
│   └── SKILL.md
├── follow-button-cta/
│   └── SKILL.md
└── past-video-gallery/
    └── SKILL.md
```

## Install

Download or clone this repository, then copy the skill folders you want into the skills directory used by your agent. For Codex, common locations are:

- **One project:** `<project>/.agents/skills/`
- **Your user account:** `~/.agents/skills/`

Keep each folder's `SKILL.md` file inside its folder. Start a new agent session after installing. You can then ask the agent to use a skill by name, for example: “Use the `spoken-kinetic-captions` skill for the key phrases in this video.”

These files are instructions for an agent, not a video editor or a one-click video generator. The agent also needs access to suitable editing tools and the project assets. Availability and installation steps may differ in other agent environments.

## What you need

- A video project and an editing tool that supports the requested effects.
- The relevant source assets, such as footage, profile artwork, or earlier video covers.
- A transcript or reliable speech timings when the effect must follow narration.

Read the inputs section of each `SKILL.md` for its specific requirements. The guides do not include sample footage, account assets, editing software, or third-party service access.

## Use and adapt

Open a skill's `SKILL.md` to review its workflow before using it. Adapt timing, placement, typography, and motion to the actual footage and the creator's style. Check the final video against the quality checks in that skill.
