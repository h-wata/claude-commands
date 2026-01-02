# daily-notes

Commands for logging work notes to Obsidian Daily notes.

## Installation

```
/install daily-notes@h-wata/claude-commands
```

## Configuration

Edit `config.json` in the plugin directory to set your Obsidian path:

```json
{
    "obsidian_daily_path": "~/Documents/my-obsidian/Daily"
}
```

## Commands

### `/memo`
Quick memo to daily note.

```
/memo Meeting finished
```

### `/work-log`
Log work based on the current conversation context.

```
/work-log
/work-log briefly
```

## Output
Notes are appended to `{obsidian_daily_path}/YYYY-MM-DD.md` with timestamp.

Example output:
```markdown
## 14:30
Meeting finished
```
