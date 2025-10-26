# Contributing to VPG Engine

Thank you for your interest in contributing to VPG Engine! This project depends on the community to document and understand the intricate mechanics of WWF No Mercy.

---
## Tools

Below are links to some of the tools being used for this project

[https://github.com/BabylonJS/Babylon.js]
[https://github.com/Rosalie241/RMG]
[https://www.blender.org/]


## 🎯 Phase 1 Goals

We are currently in the **Deep Documentation phase**. The goal is to build a comprehensive knowledge base that will guide future development.

**You do not need programming experience to contribute!** If you're passionate about No Mercy and want to help document its systems, you can make a meaningful contribution.

---

## 📋 How to Contribute

### 1. Choose a Documentation Area

Pick something you'd like to document:

#### Mechanics
- Grappling system (positions, tie-ups, move execution)
- Strike priority and counter-strike mechanics
- Momentum (Attitude) meter behavior
- Reversal windows and timing
- Damage scaling and body part targeting
- Ground game (submissions, pins, ground attacks)
- Movement physics (running, walking, rope physics)

#### Environmental
- Ring dimensions and measurements
- Collision detection points
- Rope behavior and physics
- Turnbuckle interactions
- Interactive objects (tables, ladders, chairs, etc.)
- Barricade and outside ring areas
- Arena layout standards

#### Systems
- Match types and rules
- AI behavior patterns
- Camera system and angles
- Audio cues and timing
- Special mechanics (crowd meter, etc.)

### 2. Research and Observe

Play No Mercy and carefully observe the system you're documenting:

- Take notes on behavior and timing
- Capture screenshots or video clips
- Test edge cases and interactions
- Measure distances and timing windows
- Document what you observe, even if incomplete

### 3. Create Documentation

#### For Markdown Documentation (`/docs/`)

Create a new `.md` file in the appropriate folder:

**Structure your documentation like this:**

```markdown
# [System Name]

## Overview
Brief description of what this system does and why it matters.

## Core Mechanics
Detailed explanation of how the system works.

## Observations
- Specific behaviors you've noticed
- Timing information
- Edge cases

## Open Questions
- Things that need more research
- Unclear behaviors
- Areas needing testing

## Related Systems
- Links to other documentation files
- How this interacts with other mechanics

## References
- Video timestamps
- Screenshot references
- Community findings
```

#### For JSON Schemas (`/data/schemas/`)

Create structured templates for data:

**Example Move Template:**
```json
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "title": "Move Template",
  "description": "Template for wrestling move data",
  "type": "object",
  "properties": {
    "id": {
      "type": "string",
      "description": "Unique move identifier"
    },
    "name": {
      "type": "string",
      "description": "Display name of the move"
    },
    "category": {
      "type": "string",
      "enum": ["grapple", "strike", "ground", "aerial", "special"]
    },
    "damage": {
      "type": "object",
      "properties": {
        "head": {"type": "number"},
        "body": {"type": "number"},
        "arm": {"type": "number"},
        "leg": {"type": "number"}
      }
    },
    "execution_frames": {
      "type": "number",
      "description": "Number of frames to execute"
    },
    "reversal_window": {
      "type": "object",
      "properties": {
        "start_frame": {"type": "number"},
        "end_frame": {"type": "number"}
      }
    }
  }
}
```

### 4. Submit Your Contribution

#### Option A: GitHub Pull Request (Recommended)

1. **Fork** the repository
2. **Create a branch**: `git checkout -b docs/grappling-system`
3. **Make your changes**: Add or edit documentation files
4. **Commit**: `git commit -m "Add grappling system documentation"`
5. **Push**: `git push origin docs/grappling-system`
6. **Open a Pull Request** with a clear description of what you've documented

#### Option B: GitHub Issues

If you're not comfortable with Git:

1. Open a new Issue
2. Use the label `documentation`
3. Share your findings, notes, or research
4. Someone will help format it into proper documentation

---

## 📝 Documentation Guidelines

### Be Accurate
- Document what you observe, not what you remember
- Test your observations multiple times
- Note when something is uncertain or needs verification

### Be Specific
- Include numbers, timings, and measurements when possible
- Describe exact button inputs and sequences
- Reference specific scenarios or situations

### Be Clear
- Write for someone who has never played No Mercy
- Use consistent terminology
- Define terms when first introduced

### Be Organized
- Use clear headings and structure
- Break complex systems into subsections
- Link to related documentation

### Cite Your Sources
- Reference video timestamps if applicable
- Link to screenshots in `/research/screenshots/`
- Credit community members who discovered information

---

## 🚫 What Not to Include

### No Copyrighted Content
- ❌ Character names, likenesses, or stats from WWE/WWF
- ❌ Real wrestler names or branding
- ❌ Copyrighted logos, music, or assets
- ❌ Screenshots containing copyrighted imagery (real wrestlers, logos)

### What You CAN Include
- ✅ Descriptions of game mechanics
- ✅ Technical measurements and timing data
- ✅ System behavior documentation
- ✅ Environmental measurements
- ✅ Screenshots of menus, HUD, ring elements (no real wrestlers visible)

**When in doubt, ask!** Open an issue if you're unsure whether something is appropriate.

---

## 🎨 File Naming Conventions

### Markdown Files
- Use lowercase with hyphens: `grappling-system.md`
- Be descriptive: `reversal-timing-windows.md`
- Group related files in subdirectories

### JSON Files
- Use lowercase with hyphens: `move-template.json`
- Schemas end in `-template.json` or `-schema.json`
- Reference data uses descriptive names: `confirmed-moves.json`

### Media Files
- Screenshots: `ring-dimensions-overhead.png`
- Videos: `grappling-front-facelock-demo.mp4`
- Include descriptive names that indicate content

---

## 🔍 Quality Standards

### Documentation Should Include:
- Clear, descriptive titles
- Overview/introduction section
- Detailed explanations
- Specific examples
- Open questions or areas needing research
- References to supporting materials

### Code/JSON Should Include:
- Clear comments explaining purpose
- Consistent formatting (use 2-space indentation)
- Descriptive property names
- Type definitions where applicable

---

## 🤝 Community Guidelines

### Be Respectful
- Treat all contributors with respect
- Constructive feedback only
- Assume good intentions

### Be Collaborative
- Build on others' work
- Credit contributors
- Share your findings openly

### Be Patient
- This is a long-term project
- Documentation takes time
- Quality over speed

---

## ❓ Questions?

- **General questions**: Open a GitHub Discussion
- **Specific documentation questions**: Open an Issue with the `question` label
- **Unclear guidelines**: Open an Issue tagged `meta`

---

## 🎖️ Recognition

Contributors will be recognized in:
- Project documentation
- Release notes
- Credits file (to be created)

Your contributions help preserve and celebrate one of wrestling gaming's greatest achievements. Thank you! 🤼‍♂️
