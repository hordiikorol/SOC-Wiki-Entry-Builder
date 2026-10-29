# SOC Wiki Entry Builder

A single offline HTML page that generates MediaWiki markup for:

- **Daily report** entries
- **False positive** table rows (with an optional exclusion query)
- **Asset** table rows

## Usage

1. Download the files.
2. Open `index.html` in a browser. No server, installation or internet connection is needed.
3. Fill in the fields, click **Copy**, and paste the markup into the wiki.

Nothing is saved or sent anywhere. Everything you type stays in the open page and is gone when you close it.

## Notes

- Dates are written as DD.MM.YYYY.
- **Defang** replaces dots in IP addresses and domains with `[.]` in the report.
- In the false positive tab, an exclusion query is written as `and not (...)`. Tick **Wrap in onlyinclude** if another wiki page should pull these lines in with `{{:PageName}}`.
