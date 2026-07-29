II-YEAR CSE ATTENDANCE PROJECT - SETUP NOTES
=============================================

FILES INCLUDED IN THIS FOLDER:
  - index.html        (button labels updated to II-CSE-A..F)
  - TEST.JS            (roll-number logic: 24/25 = Regular, 26 = LE;
                         jsonFileMap fixed to load each section's own JSON file)
  - II-CSE-A.json      (placeholder - empty array, add your student data)
  - II-CSE-B.json
  - II-CSE-C.json
  - II-CSE-D.json
  - II-CSE-E.json
  - II-CSE-F.json

FILES YOU NEED TO ADD YOURSELF (copy unchanged from your existing repo):
  - style.css
  - home1.css
  - logo.svg

These weren't included because I could not fetch them from GitHub to verify
I'd be copying them exactly as-is. Since the front end should stay untouched,
just copy your existing style.css, home1.css, and logo.svg files straight into
this folder - no edits needed, index.html already references them correctly.

JSON FORMAT (for each II-CSE-X.json file):
[
  { "roll-number": "24Q91A0501", "name": "STUDENT NAME" },
  { "roll-number": "24Q91A0502", "name": "ANOTHER STUDENT" }
]

Roll numbers starting with 24 or 25 = Regular
Roll numbers starting with 26       = Lateral Entry (LE)
