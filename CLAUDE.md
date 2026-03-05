# storescreens-skill

## Keep Skill Files in Sync
When modifying the skill definition, always update all four copies:
- `/Users/franciscoriordan/Documents/storescreens/storescreens-skill/SKILL.md` (canonical source)
- `/Users/franciscoriordan/Documents/storescreens/.claude/skills/storescreens/SKILL.md`
- `/Users/franciscoriordan/Documents/ccw/ccwcalc/.agents/skills/storescreens/SKILL.md`
- `/Users/franciscoriordan/Documents/Flex/.claude/skills/storescreens/SKILL.md`

Changes made to any copy must be mirrored to all four. Quickest way:
```bash
cp storescreens-skill/SKILL.md .claude/skills/storescreens/SKILL.md
cp storescreens-skill/SKILL.md /Users/franciscoriordan/Documents/ccw/ccwcalc/.agents/skills/storescreens/SKILL.md
cp storescreens-skill/SKILL.md /Users/franciscoriordan/Documents/Flex/.claude/skills/storescreens/SKILL.md
```
