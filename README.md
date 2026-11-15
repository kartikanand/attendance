# Attendance

A single-page, mobile-friendly consent form tracker for workshops. It records each attendee's consent to being emailed and to being photographed.

## Features

- Add people one at a time, or bulk-import names and emails from pasted text or a `.csv`/`.txt` file
- Optionally skip people whose email already exists when importing
- Toggle email and photo consent per person
- Live totals for people, email consents and photo consents
- Export and import a JSON backup
- Clear all entries

## Usage

No build step or dependencies. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

The import box accepts one name or email per line, or CSV with a `Name,Email` header.
