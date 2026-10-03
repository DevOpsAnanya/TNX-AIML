# AIML Weekly Learning Tracks

This repo is the home of the AIML team's weekly learning program. Each week is broken into day-wise topics split across three tracks. Every member picks one track, works through its checklist day by day, and fills in the matching progress worksheet. All three tracks are designed to move members toward machine learning.

## Tracks at a glance

| Track | Name | Who it is for | Where it goes next |
|---|---|---|---|
| **A** | Python Basics | Members who know zero or minimal coding, or are brushing up foundations | Comfortable writing small Python programs, then move to Track B |
| **B** | Advanced Python | Members comfortable with basics (variables, functions, loops), and want to move toward Python libraries | OOP, then numpy / pandas / matplotlib, then move to Track C |
| **C** | ML Fundamentals | Members who already know numpy, pandas, and matplotlib | Supervised learning, evaluation, scikit-learn, then deeper ML |

## Cadence

- **Week 1 is a special 9-day onboarding week:** it runs **Sunday 4 Oct 2026 to Monday 12 Oct 2026** (Sun, Mon, Tue, Wed, Thu, Fri, Sat, Sun, Mon). The first Sunday is **setup / orientation**, and the final Monday is **review, catch-up, and worksheet completion with no new topics**.
- **Every week after Week 1 runs Wednesday to Monday.** Wednesday is the kickoff day with the week's first topics, and Monday closes the week with review, catch-up, and worksheet completion.

## File tree

```
.
├── README.md                        # program overview: tracks, cadence
└── week-01/
    ├── README.md                    # Week 1 goal, schedule, track selection, worksheet submission
    ├── track-a/                     # Python Basics
    │   ├── checklist.md             # day-wise topic checklist
    │   └── worksheet.md             # progress worksheet to fill in
    ├── track-b/                     # Advanced Python
    │   ├── checklist.md
    │   └── worksheet.md
    └── track-c/                     # ML Fundamentals
        ├── checklist.md
        └── worksheet.md
```

## Week 1

- [Week 01: 4 Oct to 12 Oct 2026](week-01/README.md)
  - [Track A: Python Basics](week-01/track-a/checklist.md) - [worksheet](week-01/track-a/worksheet.md)
  - [Track B: Advanced Python](week-01/track-b/checklist.md) - [worksheet](week-01/track-b/worksheet.md)
  - [Track C: ML Fundamentals](week-01/track-c/checklist.md) - [worksheet](week-01/track-c/worksheet.md)

## How to track your progress

GitHub renders `- [ ]` checkboxes as **read-only** in file preview. You cannot click them in the web UI to tick them off. So each member tracks progress in their own fork:

1. **Fork this repo** to your own GitHub account using the *Fork* button, top right.
2. **Open your track's checklist** in **your fork**, for example `week-01/track-a/checklist.md`, not in the upstream repo.
3. **Click the pencil / Edit icon** in the top-right of the file view to open the editor.
4. **Flip each `- [ ]` to `- [x]`** for every item you complete, as you go.
5. **Commit the change** with the green *Commit changes* button, or use a branch and open a PR if your lead asks for one.
6. **Fill in your worksheet the same way** using the same edit-icon flow, then share a link to your filled-in worksheet in your team channel.

Because progress lives in your fork, you can never accidentally overwrite anyone else's work, and your lead can review it by opening your fork.

## Ground rules

- **Work through one track.** Do not mix tracks in a single week.
- **Every day ends with a hands-on deliverable.** Reading is not the work, running code is.
- **The final Monday introduces nothing new.** It is review, catch-up, worksheet completion.
- **Record time honestly** in the worksheet. Confidence ratings of 1 to 5 are more useful to you in weeks later than perfect completion rates.
