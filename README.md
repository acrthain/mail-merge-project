# Mail Merge Project

A simple Python script that automates personalised letter generation, replacing a placeholder in a template with each recipient's name.

## What it does

- Reads a list of invitee names from a text file
- Reads a single starting letter template containing a `[name]` placeholder
- Generates a personalised version of the letter for each name on the list
- Saves each completed letter as its own file, ready to send

## How it works

- **`main.py`** — reads the names and template, performs the placeholder replacement for each name, and writes out the individual letters
- **`Input/Names/invited_names.txt`** — the list of recipient names, one per line
- **`Input/Letters/starting_letter.txt`** — the template letter, with `[name]` marking where each recipient's name should go
- **`Output/ReadyToSend/`** — where the generated, personalised letters are saved

## Tech used

- Python 3
- File I/O (reading and writing multiple files)
- String manipulation (placeholder replacement)

## What I'd improve next

- Support multiple placeholders (e.g. `[name]`, `[date]`, `[event]`) for more flexible templates
- Add command-line arguments so file paths don't need to be hardcoded
- Add error handling for missing or empty input files

## Background

Built as part of a 100 Days of Code Python bootcamp, while working toward a software engineering internship.
