# Group 3 – AI photo trends and privacy (Graduation Project, Fall 2026)

Landing page for the Group 3 survey. It asks for the language (English / Arabic), randomly assigns
each visitor to one of four notice versions, and redirects to the matching Tally form with the
hidden fields `version` and `lang`.

| Version | Framing   | Disclosure |
|---------|-----------|------------|
| A1      | Nostalgic | Minimal    |
| A2      | Nostalgic | Full       |
| B1      | Neutral   | Minimal    |
| B2      | Neutral   | Full       |

Settings are at the top of the script in `index.html` (`FORMS` holds the Tally form ids).

Testing only (never share with participants): `?reset=1` clears the saved version, `?force=B2`
forces a version, `?lang=ar` skips the language question.
