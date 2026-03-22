# CLAUDE.md — Penguinsnowboard

## Project Overview

This is a **content-only creative writing repository** — no code, no build system, no tests. It contains **100 original bedtime stories** set in **Frostpeak Valley**, a snowy fictional world where penguins snowboard, polar bears ski, and winter creatures have gentle adventures. Each story is a playful winter allegory inspired by a Bible story, written for young children (~10 min reading time each).

The project also includes image prompts, video prompts, and a Goodnight Blessing for each story.

## Repository Structure

```
├── README.md                              # Full story index table (100 stories)
├── FROSTPEAK_100_BIBLE_BEDTIME_STORIES.md # Linked catalog of all 100 stories
├── CHARACTER_AND_STORY_GUIDE.md           # Character bios, world rules, tone guide
├── BEDTIME_FUN_RESEARCH_STYLE_GUIDE.md    # Style research and quality checklist
├── REPO_COMPARISON_NOTES.md               # Notes from cross-repo style comparison
├── INTERIM_CHECK_REPORT.md                # QA validation report
└── stories/
    ├── story_NN_slug.md                   # Individual story files (100 total)
    ├── story_03_*.html                    # HTML-rendered versions (stories 3 & 4)
    ├── story_04_*.html
    ├── images/story_NN/                   # Generated illustrations (stories 3 & 4)
    └── videos/                            # Highlight video clips (stories 3 & 4)
```

## Build / Run / Test

There are no build, run, or test commands. This is a pure Markdown content repo.

To preview stories, open any `.md` file directly or use a Markdown viewer. The two `.html` story files can be opened in a browser.

## Key Characters (Core Crew)

- **Piper Paddlefoot** — Emperor Penguin, brave and impulsive, glittery blue board
- **Barnaby Beaksworth** — Chinstrap Penguin, generous snack oracle, orange pizza-board
- **Willa Wobble** — Little Blue Penguin, quiet courage, tiny purple board
- **Bjorn Bigpaws** — Polar Bear, gentle giant on skis
- **Cleo Frostwhisker** — Arctic Fox, curious investigator
- **Magnus Mountainhorn** — Narwhal, dramatic and loyal

## Story File Format

Each story `.md` file follows this structure:

1. **Header** — Title, Bible inspiration reference, characters, setting, theme
2. **Opening Wink** — Humorous narrator aside to set the mood
3. **The Story** — Main narrative (~10 min read-aloud length)
4. **Snowy Giggle Check-In** — Mid-story engagement moment
5. **Goodnight Blessing** — Soothing closing for bedtime
6. **Image Prompts** — Detailed prompts for illustration generation
7. **Video Prompts** — Prompts for animated highlight clips

## Writing Conventions and Tone

These rules are documented in `CHARACTER_AND_STORY_GUIDE.md` and `BEDTIME_FUN_RESEARCH_STYLE_GUIDE.md`:

- **Cozy first, meaningful second** — warmth and fun always come before the moral
- **Funny always** — gentle, never mean humor; high whimsy density
- **High wonder, low fear** — every challenge ends in warmth, friendship, and hope
- **Heart-first, never preachy** — Bible allegories are reimagined playfully
- **Read-aloud clarity** — short-to-medium sentences, voice-friendly for caregivers
- **One main moral per story** — concrete allegory, fun before lesson
- Character catchphrases should appear naturally in their stories
- Stories use the naming convention `story_NN_slug_with_underscores.md`

## Branch Info

The default branch is `claude/bedtime-stories-animals-4gKbx`.
