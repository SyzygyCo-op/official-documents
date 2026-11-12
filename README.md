# Syzygy Official Documents

The official record of Syzygy's bylaws and policies.

## What this is

Each document here is the text in force today.
When a change is adopted, the text here is updated, and the change is kept on record as one amendment.
Changes that have been recorded here stay on record, so you can look back at how a document changed.

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

1. Open the document you are interested in by clicking its name.
2. Click **History**, near the top right of the document. On a phone it may be a clock symbol or behind a menu button.
3. You now see a list of every change recorded for that document, newest first. Each entry has a short description and a date.
4. Click an entry to see what it changed. Removed lines are shown in red with a minus sign (-) in front, and added lines in green with a plus sign (+). A line whose wording changed is shown twice: the old wording in red, then the new wording in green. Lines that stayed the same are shown without color, and long stretches of them are folded away. If the entry changed more than one document, all of them are shown.

To see everything in one list, open the [full history](https://github.com/SyzygyCo-op/official-documents/commits/main).
It lists every change to anything kept here, including changes to this page, so not every entry is an amendment.
The website calls one recorded change a "commit".

## For maintainers

This section is for whoever edits the files.
Readers can skip it.

Two formatting rules keep each amendment easy to read in the history.
Please follow them in every document.
A note on naming files comes after them.

### Number sections by hand

Write the section number into the heading itself:

```markdown
### 4.2 Section title
```

Never use an automatically numbered list for sections or clauses.
With automatic numbering, adding one section silently renumbers every section after it, which breaks references such as "see section 4.2" elsewhere in the documents.
With numbers written by hand, a number changes only when someone deliberately changes it, and that change shows up in the history.

Be careful with a line that starts with a number and a period or a closing parenthesis, such as `3. Text` or `3) Text`.
That is an automatically numbered list too: the page counts for itself and can show a different number from the one you typed.
Put a backslash after the number (`3\. Text` or `3\) Text`) to keep it exactly as typed.

### One clause per line

Put each clause on its own line, and never break a line in the middle of a clause, however long it gets.
Leave an empty line between clauses, because lines that directly follow each other are shown run together as one paragraph.
Start every line at the left edge: a line indented by four or more spaces is shown as a gray box of computer code.
A line that starts with `-`, `+` or `*` and a space becomes a bullet point and loses that mark, so put a backslash in front of the mark (`\-`) if the text really starts with one.

The history compares documents line by line.
When each clause is one line, a change to one clause shows up as a change to that clause and nothing else.
If a clause is split across several lines, a small change of wording can shift the line breaks and make the lines around it look changed too.

### Naming files

The table under "How to read the documents" says where each document goes.
A policy's file name is a short name for the policy in lowercase, with dashes between the words and `.md` at the end (for example `policies/example-name.md`).
Choose the name once and keep it: after a file is renamed, its History page starts at the rename and the earlier entries are harder to find.
