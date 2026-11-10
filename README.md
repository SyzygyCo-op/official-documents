# Syzygy Official Documents

The official record of Syzygy's bylaws and policies.

## What this is

Each document here is the text in force today.
When a change is adopted, the text here is updated, and the change is kept on record as one amendment.
Versions that have been recorded here stay on record, so you can look back at what a document said before.

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
4. Click an entry to see what it changed. A line that was changed is shown twice: the old wording in red with a minus sign (-) in front, and the new wording in green with a plus sign (+). Lines that stayed the same are shown without color, and long stretches of them are folded away. If the entry changed more than one document, all of them are shown.

To see the changes to all documents in one list, open the [full history](https://github.com/SyzygyCo-op/official-documents/commits/main).
The website calls one recorded change a "commit".

## For maintainers

This section is for whoever edits the files.
Readers can skip it.

Two formatting rules keep each amendment easy to read in the history.
Please follow them in every document.

### Number sections by hand

Write the section number into the heading itself:

```markdown
### 4.2 Section title
```

Never use an automatically numbered list for sections or clauses.
With automatic numbering, adding one section silently renumbers every section after it, which breaks references such as "see section 4.2" elsewhere in the documents.
With numbers written by hand, a number changes only when someone deliberately changes it, and that change shows up in the history.

Be careful with a line that starts with a number and a period, such as `3. Text`.
That is an automatically numbered list too: the page counts for itself and can show a different number from the one you typed.
Put a backslash before the period (`3\. Text`) to keep the number exactly as typed.

### One clause per line

Put each clause on its own line, and never break a line in the middle of a clause, however long it gets.
Leave an empty line between clauses, because lines that directly follow each other are shown run together as one paragraph.

The history compares documents line by line.
When each clause is one line, a change to one clause shows up as a change to that clause and nothing else.
If a clause is split across several lines, a small change of wording can shift the line breaks and make the lines around it look changed too.

### Where files go

- The bylaws are in `bylaws.md`, next to this file.
- Each policy is its own file in `policies/`, with a short name in lowercase, dashes between the words, and `.md` at the end (for example `policies/example-name.md`).
