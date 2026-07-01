# Phrasing Block Diagramming

A personal collection of **biblical phrasing** (block diagrams) for Scripture passages.

## What this is

**Phrasing** (also called block diagramming) is a way of laying out a passage so you can see its main points and flow at a glance. Words and phrases are indented to show what supports, modifies, or contrasts with what—not labeled by part of speech like traditional sentence diagramming.

Example structure:

```
[1] I charge you
        in the presence of God
            and of Christ Jesus,
                who is to judge the living and the dead,
        and by his appearing
            and his kingdom:

[2] preach the word;
        be ready
            in season
                and out of season;
        ...
```

Each diagram uses **inline verse numbers** (`[1]`, `[2]`, …) on the first phrase of each verse so you can see both the logical structure and where each verse begins.

## What this repo is for

This repository stores phrasing work for Bible passages—passage reference, translation, and the indented diagram. Use it to:

- Keep a durable archive of passages you have worked through
- Compare structure across books or pericopes
- Revisit diagrams when preparing to teach or study
- Track revisions as your understanding of a passage deepens

## What this repo is not

- Not sentence diagramming (subject/predicate/object trees)
- Not a commentary or sermon archive
- Not tied to a single translation—each file should note which translation was used

## Organization

**Passage files** live under `phrasing/`, organized by testament with numbered book folders:

```
phrasing/
  OT/
    19-psalms/
      psalms-133-esv.md
  NT/
    05-acts/
      acts-02-42-47-esv.md
    06-romans/
      romans-12-09-13-esv.md
    16-2-timothy/
      2-timothy-04-01-05-esv.md
```

**Filename convention** — zero-pad numeric segments so files sort in biblical order:

| Book type | Pattern | Example |
|-----------|---------|---------|
| Most books (range) | `{book}-{cc}-{vv}-{vv-end}-{translation}.md` | `hebrews-03-12-14-esv.md` |
| Single verse | `{book}-{cc}-{vv}-{translation}.md` | `galatians-03-28-esv.md` |
| Whole psalm | `psalms-{ccc}-{translation}.md` | `psalms-023-esv.md`, `psalms-133-esv.md` |
| Psalm range | `psalms-{ccc}-{vvv}-{vvv-end}-{translation}.md` | `psalms-119-001-008-esv.md` |

Chapters and verses use **two digits**; Psalms use **three digits** (psalms 1–150; verses up to 176).

**Topic collections** (e.g. a sermon series) get a folder under `Topics/` with review and prep documents that link to the individual passage files:

```
Topics/
  community-groups/
    community-groups-passages.md
    john-piper-on-community-groups.md
    mark-dever-on-community-groups.md
```

Each passage file typically includes:

1. **Reference and translation** (e.g. 2 Timothy 4:1–5, ESV)
2. **Whole-passage flow** — complete text with indentation and verse numbers
3. **Optional notes** — brief comments on structure or interpretive choices

## Working with Cursor

Phrasing in this repo can be produced with the Cursor skill **`phrasing-block-diagramming`** (personal skill). Ask for a block diagram or phrasing of a passage; save the result here when you want it in version control.

## License

Personal study material. Scripture quotations remain the property of their respective copyright holders (ESV, NIV, etc.); note the translation in each file.
