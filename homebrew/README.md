# Homebrew Content

This directory contains original D&D homebrew organized by content type and, where applicable, the primary class it supports.

## Directory layout

```text
homebrew/
└── subclasses/
    └── <primary-class>/
        ├── <subclass-document>.md
        └── images/
            └── <subclass-artwork>.<extension>
```

### Subclasses

Store each subclass under the lowercase name of its primary class:

- `homebrew/subclasses/barbarian/`
- `homebrew/subclasses/bard/`
- `homebrew/subclasses/cleric/`
- `homebrew/subclasses/druid/`
- `homebrew/subclasses/fighter/`
- `homebrew/subclasses/monk/`
- `homebrew/subclasses/paladin/`
- `homebrew/subclasses/ranger/`
- `homebrew/subclasses/rogue/`
- `homebrew/subclasses/sorcerer/`
- `homebrew/subclasses/warlock/`
- `homebrew/subclasses/wizard/`

Create a class directory when the first subclass for that class is added; do not create empty placeholder directories.

Keep artwork used by a subclass in that subclass's local `images/` directory. Markdown image links should remain relative to the document so the complete subclass can be moved or shared as a unit.

## Current content

- `subclasses/cleric/sword-dancer-domain-v1.md` — **Sword Dancer Domain**, a Cleric subclass for the 2024 D&D rules / 5.5e.
  - Artwork is archived in `subclasses/cleric/images/`.

## Naming conventions

- Use lowercase class directory names.
- Use descriptive, hyphenated document filenames with a version suffix when the document has distinct revisions.
- Keep the edition and version in the document's title/subtitle so the file remains self-describing outside the repository.
