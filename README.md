# Syzygy Official Documents

The official record of Syzygy's bylaws and policies.

## What this is

Each document here is the text in force today.
When a change is adopted, the text here is updated, and the change is kept on record as one amendment.
Earlier versions are never thrown away, so you can always look back at what changed and when.

This is a place to read the documents and to check what changed.
You do not need an account, and you do not need to install or learn anything.

## How to read the documents

Each document is one file.
The files are listed on the [front page](https://github.com/SyzygyCo-op/official-documents), above this text.
Click a file's name to open it and read it.

| File | What it holds |
|---|---|
| `bylaws.md` | The bylaws. |
| `policies/` | A folder with one file for each policy. Each file has a short name for its policy, in lowercase with dashes between the words. |

The documents are being added one at a time, so a file may not be here yet.
A missing file only means the document has not been added here so far.
It does not mean the document is not in force.

## How to see what changed

Every document keeps a history: one entry for each change recorded here.
A document's oldest entry is the one that added it here.
Its history starts there, even if the document itself is older.
Most entries are amendments.
Now and then one is housekeeping, such as correcting a mistake made while copying a document in, and its description says so.

1. Open the document you are interested in by clicking its name.
2. Click **History**, near the top right of the document. On a phone it may be a clock symbol or behind a menu button.
3. You now see a list of every change recorded for that document, newest first. Each entry has a short description and a date.
4. Click an entry to see what it changed.
   Removed lines are shown in red with a minus sign (-) in front, and added lines in green with a plus sign (+).
   A line whose wording changed is shown twice: the old wording in red, then the new wording in green.
   Lines that stayed the same are shown without color, and long stretches of them are folded away.
   If the entry changed more than one document, all of them are shown.

To see everything in one list, open the [full history](https://github.com/SyzygyCo-op/official-documents/commits/main).
It lists every change to anything kept here, including changes to this page.
The website calls one recorded change a "commit".

## For maintainers

This section is for whoever edits the files.
Readers can skip it.

Two formatting rules keep each amendment easy to read in the history.
After them come a few traps to avoid, and a note on naming files.

### Number sections by hand

Write the section number into the heading itself:

```markdown
### 4.2 Section title
```

Never use an automatically numbered list for sections or clauses.
With automatic numbering, adding one section silently renumbers every section after it, which breaks references such as "see section 4.2" elsewhere in the documents.
With numbers written by hand, a number changes only when someone deliberately changes it, and that change shows up in the history.

### One clause per line

Put each clause on its own line, and never break a line in the middle of a clause, however long it gets.
Leave an empty line between clauses, because lines that directly follow each other are shown run together as one paragraph.

The history compares documents line by line.
When each clause is one line, a change to one clause shows up as a change to that clause and nothing else.
If a clause is split across several lines, a small change of wording can shift the line breaks and make the lines around it look changed too.

### Traps to avoid

The files are written in Markdown, which treats the start of a line specially in a few cases.
Each one changes how the text is shown without any warning, so look at the finished page after editing.

- A line that starts with a number, then a period or a closing parenthesis, then a space (`3. Text` or `3) Text`) becomes an automatically numbered list.
  The page counts for itself and can show a different number from the one you typed, and it shows a parenthesis as a period.
  Put a backslash after the number (`3\. Text` or `3\) Text`) to keep it exactly as typed.
- A line that starts with `-`, `+`, `*`, `#` or `>` and a space loses that mark and becomes a bullet point, a heading or a quotation.
  Put a backslash in front of the mark (`\-`) if the text really starts with one.
- A line made only of dashes or underscores becomes a horizontal rule.
- A line that starts with a tab or with four or more spaces is shown as a gray box of computer code.
  Start every line at the left edge.

### Naming files

[How to read the documents](#how-to-read-the-documents) says where each document goes and how policy files are named.
Every file name ends in `.md` (for example `policies/example-name.md`).
Choose the name once and keep it, even if the document's title later changes.
After a file is renamed, its History page starts at the rename, and the earlier entries stay behind under the old name.
