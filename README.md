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

<img width="1532" height="912" alt="image" src="https://github.com/user-attachments/assets/874effc8-23b3-4418-966c-d38531cd6298" />

<img width="1537" height="882" alt="image" src="https://github.com/user-attachments/assets/fd9acbe0-e72f-4a2c-8922-07df57039d86" />

<img width="1541" height="917" alt="image" src="https://github.com/user-attachments/assets/4e1c2e06-a97f-4551-a1fd-567d4f8ddc43" />
