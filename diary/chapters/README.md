# Published chapters

Create one directory per chapter or arc when useful for organization. Entries
retain stable paths and their source session IDs and consulted memory record IDs
in front matter. Use only `status: draft` or `status: published`; the site lists
only published content.

Use `.agents/templates/chapter.md` for the chapter index and
`.agents/templates/act.md` for its acts. The act's `chapter` value must match the
chapter's `slug` so the site can collect and order acts automatically.
