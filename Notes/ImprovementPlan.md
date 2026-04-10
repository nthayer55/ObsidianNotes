# Improvement Plan for Obsidian Vault

This document outlines actions you need to take to further enhance your Obsidian vault's organization and connectivity. These are things I can't do directly, like installing plugins or configuring settings.

## 1. Install Essential Plugins
Install these plugins via Obsidian's Community Plugins browser (Settings > Community plugins > Browse):

- **Dataview**: For dynamic queries and lists (e.g., list all #fitness notes). Essential for connectivity.
- **Kanban**: Create task boards from your Tasks.md or for projects.
- **Templates**: Use the templates in `Templates/` folder for new notes.
- **Daily Notes**: Set up daily journaling with links to tasks and goals.
- **Tag Pane**: Visualize and navigate tags easily.
- **Backlinks**: Ensure backlinks are visible (usually enabled by default).
- **Graph View**: Visualize note connections (enabled by default).

## 2. Configure Core Settings
In Obsidian Settings:
- **Files & Links > New link format**: Set to "Relative path to file" for cleaner links.
- **Files & Links > Automatically update internal links**: Enable to update links when renaming files.
- **Editor > Show frontmatter**: Enable to see YAML metadata (tags, etc.).
- **Daily Notes**: Configure the folder and template (use `Templates/Daily Note Template.md`).

## 3. Set Up Templates
- Go to Settings > Templates > Template folder location: Set to `Templates/`.
- When creating new notes, use the template picker to apply the appropriate template.

## 4. Enable Dataview Queries
Add Dataview codeblocks to MOCs for dynamic content. For example, in `00-Gym MOC.md`, add:

```
## Recent Fitness Notes
```dataview
LIST
FROM #fitness
SORT file.mtime DESC
LIMIT 5
```

This will automatically list recent fitness-tagged notes.

## 5. Regular Maintenance Tasks
- **Weekly Review**: Check backlinks on key notes to find linking opportunities.
- **Tag Audit**: Search for untagged notes and add relevant tags.
- **Link Updates**: After renaming files, use Obsidian's "Update internal links" feature.
- **Archive Old Notes**: Move outdated notes to an `Archive/` folder to keep the vault focused.

## 6. Advanced Features to Explore
- **Properties (YAML Frontmatter)**: Add metadata like `date: 2026-04-10` to notes for better querying.
- **Canvas**: For visual mind maps connecting ideas.
- **Publish**: If you want to share parts of your vault online.
- **Sync**: Set up Obsidian Sync for cross-device access.

## 7. Habit Building
- **Link as You Write**: When mentioning concepts, link to related notes immediately.
- **Use Tags Consistently**: Develop a tag hierarchy (e.g., #work/meeting, #fitness/goals).
- **Review Graph View**: Regularly explore the graph to spot disconnected clusters.

## 8. Backup and Safety
- Enable Obsidian's backup features.
- Consider Git versioning for your vault (if comfortable with command line).

Start with installing Dataview and Templates—these will unlock powerful connectivity features!